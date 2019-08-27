# How many people are in full-time employment in Wales

***If you've not read the tables and filters sections, you should still be able to make sense of this example, although we will be refering to those sections through this example.***

With the Census data, there are several ways to get what you want, these different ways don't neccessarily have names, but we'll go through them anyway. Before we do this, we need to determine what we're actually searching for.

> How many people are in full-time employment in Wales.

We know that we're looking for:

- `people`
- `full-time employment`
- `Wales`

We know that `people` is the UNIT, so we can find out what the first filter will be. To do this we'll look at the [codelist_def](../tables/codelist_def.md) AND [codes](../tables/codes.md)table. Since we know the topic [MNU](../fields/mnu.md) is `UNIT`, we can perform the following query:

```sql
SELECT ID, NAME, MNU FROM codelist_def WHERE MNU = 'UNIT';
```
|ID|NANE|MNU|
|-|-|-|
|68|Unit|UNIT|

Given that we know the `ID = 68`, we can now perform the next query which will show us a list of `filters` for this topic.

```sql
SELECT CLID, ID, DESCRP FROM codes WHERE CLID = 68;
```

|CLID|ID|DESCRP|
|-|-|-|
|68|1962|Persons|
|68|1963|Hectares|
|68|1964|Households|
|68|1965|Dwellings|
|68|1966|Rooms|
|68|1967|Bedrooms|
|68|1968|Cars or vans|
|68|1969|Communal establishments|
|68|1970|Families|
|68|1971|Household spaces|
|68|4232|Kilometres|
|68|4235|Years|

Given that we know we're looking for something like `people`, we can now use the following row.

|CLID|ID|DESCRP|
|-|-|-|
|68|1962|Persons| 

We know now we have a [CLS](../fields/cls.md) field of `UNIT:1962`.

The next things for us to look at is what `full-time` employment means. To do this I would simply perform a query that returns a list of `topics` and I can use my own judgement to decide which is best. We can do this with by looking at the [codelist_def](../tables/codelist_def.md) table again.

```sql
SELECT ID, NAME, MNU FROM codelist_def;
```

|ID|NAME|MNU|
|-|-|-|
|...|...|...|
|17|Dwellings|DWLTYP|
|18|Economic Activity|ECOACT|
|19|Economic activity of Household Reference Persons|ECPHRP|
|...|...|...|

In reality, you would have to go through them all and decide for yourself. However, because I know what `topic` is best for this, we will use `ECOACT`, where `ID = 18`.

Now we need to find with `filter` we need. We can do this by performing the same query to the [codes](../tables/codes.md) tables as we did above:

```sql
SELECT CLID, ID, DESCRP FROM codes WHERE CLID = 18;
```

You'll notice that if you've run this query yourself, there are 155 rows returned, and we're looking for something like `full-time employment`. However, this is very ambigious. Here's some of examples of `filters` that may appear to mean `full-time emplyoment`:

|CLID|ID|DESCRP|
|-|-|-|
|18|565|Economically active|
|18|566|Employed|
|18|568|Full-time|
|18|571|In employment|
|18|577|Full-time|
|18|588|In employment the week before the census"
|18|591|Full-time|
|18|594|Full-time|
|18|2276|Full-time|
|18|2277|Full-time (including full-time students)|
|18|2285|Full-time|
|18|2292|Full-time|
|18|2293|(inclduing full-time students)|
|18|3795|Full-time (excluding full-time students)|
|18|3797|Full-time (excluding full-time students)|
|18|3799|Full-time (excluding full-time students)|
|...|...|...|

The point I'm trying to make here is that there are often (especially for `ECOACT`) many different `filters` that might make sense. The easiest way to describe why this appears to be the case is that certain [CLS](../filters/cls.md) don't go together. We'll see this shortly. 

Since we're not sure exactly which one to go for, let's pick the first one from that list and search [cellmaps](../tables/cellmaps.md) table:

```sql
SELECT * FROM cellmaps WHERE UNIT = 1962 AND ECOACT = 568;
```

With these query, we get lucky, we get the following [IS_ID](../fields/id_id.md) fields returned:

|IS_ID|
|-|
|306588|
|306604|
|306615|

This means that there are 3 combinations of filters that include `UNIT = 1962` and `ECOACT = 568`. We can perform a query to find the [CL_CODE](../filters/cl_code.md) field from the [codelist_cube_description](../tables/codelist_cube_description.md) table:

```sql
SELECT IS_ID, CELLNAME, CL_CODE, GL_EXTENTS FROM codelist_cube_description WHERE IS_ID IN (306588, 306604,306615);
```

|IS_ID|CELLNAME|CL_CODE|GL_EXTENTES
|-|-|-|-|
|306588|KS601NI0003|AGE:46,ECOACT:568,UNIT:1962|2003:5,2006:5,2007:5,2009:5,2010:5|
|306604|KS602NI0003|AGE:46,ECOACT:568,SEX:1932,UNIT:1962|2003:5,2006:5,2007:5,2009:5,2010:5|
|306615|KS603NI0003|AGE:46,ECOACT:568,SEX:1933,UNIT:1962|2003:5,2006:5,2007:5,2009:5,2010:5|

So far this looks great! But... no. This is the point where we realise why it matters which `ECOACT` we chose. If we look closely at the [GL_EXTENTS](../fields/gl_extents.md) that we have been returned, we can see they are all for Northern Ireland:

- `2003:5` - Countries : Northern Ireland
- `2006:5` - Local Authorities : NorthernIreland
- `2007:5` - Wards and Electoral Divisions : Northern Ireland
- `2009:5` - Lower Super Output Areas & Data Zones : Northern Ireland
- `2010:5` - Output Areas and Small Areas : Northern Ireland

What we need to do is figure out which `filter` for `ECOACT` contains information about `full-time employment` **and** is available in `Wales`. There are several ways we can do this. One way to do this includes searching the [cellmaps](../tables/cellmaps.md) table `JOINED` with the [codelist_cube_description](../tables/codelist_cube_description.md) table `ON  cellmaps.IS_ID = codelist_cube_description.IS_ID `. We can now search against the [GL_EXTENTS](../fields/gl_extents.md) field to get the following query:

```sql
SELECT 
codelist_cube_description.CL_CODE,
cellmaps.*,
codelist_cube_description.GL_EXTENTS 
FROM infuse2011.cellmaps

JOIN infuse2011.codelist_cube_description ON cellmaps.IS_ID = codelist_cube_description.IS_ID

WHERE codelist_cube_description.GL_EXTENTS LIKE '%2003:5%'

AND cellmaps.UNIT = 1962

AND cellmaps.ECOACT IN (577, 591, 594);
```

This query looks very complicated (compared to all our others). Essentially all it's doing is combining the two tables so we can filter the results by[GL_EXTENTS](../fields/gl_extents.md).

You will notice that we have done `cellmaps.ECOACT IN (577, 591, 594)`. These are 3 randomly picked `filters` from `ECOACT` that we believe to represent `full-time employment`.

When we actually run this query, we get 2874 rows returned. This is way too many for any of us to go through. Keep in mind, we're wanting one row in the end. The next thing we can do is just pick the one with the smallest [CL_CODE](../fields/cl_code.md) length. For now, you can be manual about this (keeping in mind that there are multiple ways to get the right answer).

For now, we've got the following [CL_CODEs](../fields/cl_code.md) and [IS_IDs](../fields/is_id.md):
|IS_ID|CL_CODE|
|-|-|-|
|260|AGE:46,ECOACT:577,UNIT:1962|
|557|AGE:46,ECOACT:591,UNIT:1962|
|559|AGE:46,ECOACT:594,UNIT:1962|

You will notice two things:

- The [CL_CODEs](../fields/cl_code.md) all have an extra `field` and `topic`, `AGE:46`
- Each has a different `ECOACT`

First, let's find out what `AGE:46` means, using the following query:

```sql
SELECT CLID, ID, DESCRP FROM codes WHERE ID = 46;
```

|CLID|ID|DESCRP|
|-|-|-|
|3|46|Age 16 to 74|

If you think about it, this makes sense. Of course we're going to need an `AGE filter`. If we're talking about people who are working, the person **HAS** to be over the age of 16. Since we've got 3 `ECOACT`s to chose from, let's just use `577`, so now we have and `IS_ID = 260`, nice. Let's perform another query to get the [INFUSE_TABLE_NAME](../fields/infuse_table_name.md) and [CELLNAME](../fields/cellname.md) fields.

```sql
SELECT IS_ID, CELLNAME, INFUSE_TABLE_NAME FROM infuse2011.cube_description WHERE IS_ID = 260;
```

You'll notice that we get 3 rows. This makes sense as there are 3 filters. If you don't fully understand this, that's fine. You will.

|IS_ID|CELLNAME|INFUSE_TABLE_NAME|
|-|-|-|
|260|QS601EW0004|QS601_0_EW_MRG_RCD_AGG|
|260|QS601EW0004|QS601_0_EW_MRG_RCD_AGG|
|260|QS601EW0004|QS601_0_EW_MRG_RCD_AGG|

Now that we know 