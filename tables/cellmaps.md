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

This table does also includes the geolocation information represented by the following columns:

- GL_2000
- GL_2001
- GL_2002
- GL_2003
- GL_2004
- GL_2005
- GL_2006
- GL_2007
- GL_2008
- GL_2009
- GL_2010
- GL_2011
- GL_2012
- GL_2013

The columns contain a comma seperated list of extents, i.e:

|GL_2003|
|-|
|3,4,5|

With this information you can perform a query based on topics, filters and geolocations in one table.

```sql
SELECT * FROM cellmaps WHERE
AGE = 46 AND
ECOACT = 588 AND
GL_2004 LIKE '%4%';
```