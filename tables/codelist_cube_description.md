# tables/codelist_cube_description

The `codelist_cube_description` table is almost an extension of the [codelist_combo](codelist_combo.md) table. Where the [codelist_combo](codelist_combo.md) table described and explained combinations of `topics`, the `codelist_cube_description` tables describes and explains combinations of `topics` and `filters`.

The [codelist_combo](codelist_combo.md) table may return a [CLS](../columns/cls.md) of: `AGE, COB, HIQUAL, UNIT`, the `codelist_cube_description` table will return a [CLS](../columns/cls.md) of: `AGE, COB, HIQUAL, UNIT` and [CODES](../columns/codes.md) of: `45, 246, 1006, 1962`. These [CODES](../columns/codes.md) represent the indvidual `filters` for the given `topic`, meaning that:

```yaml
AGE: 45
COB: 246
HIQUAL: 1006
UNIT: 1962
```

You can these use the [codes](codes.md) table to find out what these paramaters actually are.

This table not only tells you what `filters` work together, it also tells you what locations there are available for, [GL_EXTENTS](../columns/GL_EXTENTS.md).

```sql
SELECT IS_ID, CELLNAME, CODES, CLS, CL_CODE, GL_EXTENTS FROM codelist_cube_description WHERE CLS = 'AGE, COB, HIQUAL, UNIT' LIMIT 3;
```

|IS_ID|CELLNAME|CODES|CLS|CL_CODE|GL_EXTENTS|
|-|-|-|-|-|-|
|330371|DC5203EW0053|45, 246, 1006, 1962|AGE, COB, HIQUAL, UNIT|AGE:45, COB:246, HIQUAL:1006, UNIT:1962|2002:3, 2003:4, 2003:7, 2004:4, 2005:4, 2006:4, 2006:7, 2007:4, 2007:7, 2008:4, 2008:7, 2011:4|
|330372|DC5203EW0054|45, 247, 1006, 1962|AGE, COB, HIQUAL, UNIT|AGE:45, COB:247, HIQUAL:1006, UNIT:1962|2002:3, 2003:4, 2003:7, 2004:4, 2005:4, 2006:4, 2006:7, 2007:4, 2007:7, 2008:4, 2008:7, 2011:4|
|330373|DC5203EW0055|45, 248, 1006, 1962|AGE, COB, HIQUAL, UNIT|AGE:45, COB:248, HIQUAL:1006, UNIT:1962|2002:3, 2003:4, 2003:7, 2004:4, 2005:4, 2006:4, 2006:7, 2007:4, 2007:7, 2008:4, 2008:7, 2011:4|

The table above shows us possible `filter` combinations along with the available `geolocations`.
