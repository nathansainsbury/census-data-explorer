# fields/CL_CODE

The [CL_CODE](cl_code.md) is a combination of `filters` and `topics`, which is found in the [codelist_cube_description](../tables/codelist)cube_description.md) table.

```sql
SELECT IS_ID, CODES, CLS, CL_CODE FROM codelist_cube_description;
```

|IS_ID|CODES|CLS|CL_CODE|
|-|-|-|-|
|1|10, 1962, 1975|ACCTY, UNIT, URESPOP|ACCTYP:10, UUNIT:1962, URESPOP:1975|
|...|...|...|...|
|30|15, 39, 1962, 1975|ADLFA, AGE, UNIT, URESPOP|ADFLA:15, AGE:39, UNIT:1962, URESPOP: 1975|
|...|...|...|...|
|78|126, 1962|AGE, UNIT|AGE:126, UNIT:1962|
|...|...|...|...|

Let's look at `IS_ID = 78`. Here the [CL_CODE](cl_code.md) contains:

- AGE: 126
- UNIT: 1962

Using the [codes](../tables/codes.md) we can perform the following query to find out what this means, by using the `filters`.

```sql
SELECT CLID, ID, DESCRP FROM codes WHERE ID IN (126, 1962);
```
|CLID|ID|DESCRP|
|-|-|-|
|3|126|Age 73|
|68|1962|Persons|

From this we can infer that where `IS_ID = 78`, the data is refering to how many 73 year olds live in a given [GL_EXTENTS](gl_extents.md).

In practice, there's never a need to directly use this field as it's just a combination of [CODE](codes.md) and [CLS](cls.md).
