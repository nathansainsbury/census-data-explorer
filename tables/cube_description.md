# tables/cube_description

The `cube_description` table is the final table you need to query before you can actually query for the data you want. Once you've found the relevant [IS_ID](columns/is_id) from the [codelist_cube_description](tables/codelist_cube_description) table, you can perform the following query.

```sql
SELECT CELLNAME, IS_ID, MNU, INFUSE_TABLE_NAME FROM cube_description WHERE IS_ID = 330372;
```

|CELLNAME|IS_ID|MNU|INFUSE_TABLE_NAME|
|-|-|-|-|
|DC5203EW0054|330372|AGE|DC5203_0_EW_MRG_RCD_AGG|
|DC5203EW0054|330372|COB|DC5203_0_EW_MRG_RCD_AGG|
|DC5203EW0054|330372|HIQUAL|DC5203_0_EW_MRG_RCD_AGG|
|DC5203EW0054|330372|UNIT|DC5203_0_EW_MRG_RCD_AGG|

You will notice that although this query has returned 4 rows, they all have the same [INFUSE_TABLE_NAME](columns/infuse_table_name.md). You can use any of these rows, and use [INFUSE_TABLE_NAME](columns/infuse_table_name.md) to query the revelevant data table with the relevant `geolcation`.