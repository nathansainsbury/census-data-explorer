# fields/CELLNAME

The [CELLNAME](cellname.md) field can be found in the [codelist_cube_description](../tables/codelist_cube_description.md) table. When used in conjuction with [GL_EXTENTS](gl_extents.md) and [INFUSE_TABLE_NAME](infuse_table_name.md), relevant data can be found.

The [CELLNAME](cellname.md) field indicates the `field` you need when querying the relevent data. For example, let's say you have:

- `INFUSE_TABLE_NAME`: QS402_0_EW_MRG_RCD_AGG
- `CELLNAME`: QS402EW0009


You can the perform the following query:

```sql
SELECT GEOCODEID, CL_ID, QS402EW0009 FROM QS402_0_EW_MRG_RCD_AGG;
```

|GEOCODEID|CL_ID|QS402EW0009|
|-|-|-|
3| 2002| 860207
4| 2003| 834083
5| 2003| 5340
6| 2003| 41668
7| 2003| 26124
8| 2004| 24264
9| 2004| 59284
|...|...|...|

We can now use this table to determine that for where the [GL_EXTENTS](gl_extents.md) is `2003:5`, the value is 5340.

Working back from this, because we know that [CELLNAME](cellname.md) relates to the [IS_ID](is_id.md) of 2, and that:

```sql
SELECT CL_CODE FROM codelist_cube_description WHERE IS_ID = 2;
```

|CL_CODE|
|-|
|ACCTYP:10,UNIT:1964|

```sql
SELECT ID, DESCRP FROM infuse2011.codes  WHERE ID IN (10, 1964);
```
|ID|DESCRP|
|-|-|
|10| Part of a converted or shared house (including bed-sits)|
|1964| Households|

We now that the the value `5340` represents the amount of households (`1964`) that are converted or shared housing (`10`) in Northern Ireland (`2003:5`)
