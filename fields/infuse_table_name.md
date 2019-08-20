# fields/INFUSE_TABLE_NAME

The [INFUSE_TABLE_NAME](infuse_table_name.md) can be found in the [cube_description](../tables/cube_description.md) table. Once you have found your [IS_ID](is_id.md), you can then use that to find the [INFUSE_TABLE_NAME](infuse_table_name.md) with a query like:

```sql
SELECT ID, CELLNAME, IS_ID, INFUSE_TABLE_NAME FROM infuse2011.cube_description WHERE IS_ID;
```
|ID|CELLNAME|IS_ID|INFUSE_TABLE_NAME|
|-|-|-|-|
|4|QS402EW0009|2|QS402_0_EW_MRG_RCD|
|5|QS402EW0009|2|QS402_0_EW_MRG_RCD|

The [INFUSE_TABLE_NAME](infuse_table_name.md) can then be used to query the actual data you want given that you have the [GL_EXTENTS](gl_extents.md) and the [CELLNAME](cellname.md).