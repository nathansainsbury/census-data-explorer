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
SELECT CL_ID, ID, DESCRP, NESTED_DESCRP FROM codes WHERE CL_ID = 68;
```

|CL_ID|ID|DESCRP|NESTED_DESCRP|
|-|-|-|-|
|68|1962|Persons|Persons|
|68|1963|Hectares|Hectares|
|68|1964|Households|Households|
|68|1965|Dwellings|Dwellings|
|68|1966|Rooms|Rooms|
|68|1967|Bedrooms|Bedrooms|
|68|1968|Cars or vans|Cars or vans|
|68|1969|Communal establishments|Communal establishments|
|68|1970|Families|Families|
|68|1971|Household spaces|Household spaces|
|68|4232|Kilometres|Kilometres|
|68|4235|Years|Years|

Given that we know we're looking for something like `people`, we can now use the following row.

|CL_ID|ID|DESCRP|
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
SELECT CLID, ID, DESCRP, NESTED_DESCRP FROM codes WHERE CLID = 18;
```

You'll notice that if you've run this query yourself, there are 155 rows returned, and we're looking for something like `full-time employment`. If you were to soley look at the DESCRP field you would see a lot of repetition for `Full-time`. However the [NESTED_DESCRP](../fields/nested_descrp.md) field alleviates the problem of ambiguity. A lot of [filters](../filters.md) are actually children of other [filters](../filters.md).

Even though there may be many results for `Full-time`, they are all different:

```sql
SELECT ID, CL_ID, DESCRP, NESTED_DESCRP
FROM infuse2011.codes
WHERE DESCRP = 'Full-time'
AND CL_ID = 18;
```

|CL_ID|ID|DESCRP|NESTED_DESCRP|
|-|-|-|-|
568| 18| Full-time| Economically active\ Employed\ Full-time
577| 18| Full-time| Economically active\ Employee\ Full-time
591| 18| Full-time| Economically active\ Self-employed with employees\ Full-time
594| 18| Full-time| Economically active\ Self-employed without employees\ Full-time
2276| 18| Full-time| Economically active\ In employment\ Employee\ Full-time
2285| 18| Full-time| Economically active\ In employment\ Full-time students\ Full-time
2292| 18| Full-time| Economically active\ In employment\ Self-employed\ Full-time
3917| 18| Full-time| Economically active\ In employment\ Self-employed with employees\ Full-time
3924| 18| Full-time| Economically active\ In employment\ Self-employed without employees\ Full-time
3927| 18| Full-time| Economically active\ Self-employed\ Full-time
3950| 18| Full-time| Economically active\ In employment\ Full-time
4007| 18| Full-time| Self-employed with employees\ Full-time
4010| 18| Full-time| Self-employed without employees\ Full-time
4930| 18| Full-time| Economically active (including full-time students)\ In employment\ Self-employed without employees\ Full-time
4935| 18| Full-time| Economically active (including full-time students)\ In employment\ Self-employed with employees\ Full-time

It is quite clear now how ambigious the DESCRP field, the [NESTED_DESCRP](../fields/nested_descrp.md) field is much more descreptive.

The problem doesn't quite finish here. We know 2 things for definite:

- UNIT: 1962
- 2003: 7 (Wales)

However not all of the rows in the table above are necessarily found in conjuction with:

```sql
UNIT = 1962 AND GL_2003 LIKE '%7%';
```

The only way to test this would be to select a few [filter](../filters.md) options for `ECOACT` and check the [cellmaps](../tables/cellmaps.md) table.

```sql
SELECT * FROM cellmaps WHERE
UNIT = 1962 AND
GL_2003 LIKE '%7%' AND
ECOACT IN (568, 577, 2276);
```

This will return 1315 rows.
