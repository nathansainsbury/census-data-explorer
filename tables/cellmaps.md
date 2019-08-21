# tables/cellmaps

The [cellmaps](cellmaps.md) is a very intutitive table. It consists of an [IS_ID](../fields/is_id.md) field, a [CELLNAME](../fields/cellname.md) field and a list of all the `filters`, i.e 


- `ABDPEWE`
- `ABWELCH`
- `ACCTYP`
- `...`

Given that you know the `topics` and `filters` you want the data for you can find the releveant [CELLNAME](../fields/cellname.md) and thus the relevant [INFUSE_TABLE_NAME](../fields/infuse_table_name.md).

Let's say you have:

- `ACCTYP`: 10
- `UNIT`: 1962
- `URESPOP`: 1975

You can perform the following query:

```sql
SELECT * FROM cellmaps WHERE ACCTYP = 10 AND UNIT = 1962 AND URESPOP = 1975;
```

Which will return a table with 173 columns and 12 rows.

|IS_ID|CELLNAME|...|ACCTYP|...|TENURE|...|UNIT|...|URESPOP|...|
|-|-|-|-|-|-|-|-|-|-|-|
|1|QS401EW0009|...|10|...|NULL|...|1962|...|1975|...|
|258269|DC4403NI0089|...|10|...|1936|...|1962|...|1975|...|
|258270|DC4403NI0090|...|10|...|3340|...|1962|...|1975|...|
|...|...|...|...|...|...|...|...|...|...|...|

You will notice that this table has a field called `TENURE` which is `NULL` for the first result. This basically means that the given combination exists, but it also exists with extra topics. An example of this is that you can calculate how many people are in full-time work (`ECOACT`) and you can also calculate the religion (`RELIG`) of the people in full-time work.

This table does not tell you the `GEOLOCATION` of where the data is available. For this you can use the [IS_ID](../fields/is_id.md) found in this table to query the [codelist_cube_description](codelist_cube_description.md) table:

```sql
SELECT IS_ID, GL_EXTENTS FROM codelist_cube_description WHERE IS_ID = 1;
```

|IS_ID|GL_EXTENTS|
|-|-|
|1|2002:3, 2003:4, 2003:5, 2003:6, 2003:7, 2004:4, 2005:4, 2006:4, 2006:5, 2006:6, 2006:7, 2007:4, 2007:5, 2007:6, 2007:7, 2008:4, 2008:6, 2008:7, 2009:4, 2009:5, 2009:6, 2009:7, 2010:4, 2010:5, 2010:6, 2010:7, 2011:4, 2012:4, 2012:7|