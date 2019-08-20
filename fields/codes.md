# fields/CODES

The [CODES](codes.md) field can be found in the [codelist_cube_description](../tables/codelist_cube_description.md) table and is a comma seperated list filter ids, which can be found in the [codes](../tables/codes.md) table with the `ID` field.

```sql
SELECT IS_ID, CODES FROM codelist_cube_description;
```

|IS_ID|CODES|
|-|-|
|1|10, 1962, 1975|
|2|10, 1964|
|3|11, 1962, 1975|
|...|...|

These [CODES](codes.md) are the `filter` ids for a given `topic`. You can find the definitions of these [CODES](codes.md) by performing the following query:

```sql
SELECT  CLID, ID, DESCRP FROM code WHERE ID IN (11, 1962, 1975);
```

|CLID|ID|DESCRP|
|-|-|-|
|1|11|In commercial building|
|68|1962|Persons|
|69|1975|All usual residents in households|
