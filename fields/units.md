# fields/UNITS

The [UNITS](units.md) field indicates what data the unit represents. For example, if you were to query something like:

> How many Sikh's work in England?

The `unit` would be people, `1962`. 

The total list of [UNITS](units.md) can be found by performing the following query:

```sql
SELECT CLID, ID, DESCRP FROM codes WHERE CLID = 68;
```

|CLID|ID|DECRP|
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

It's best not to think of [UNITS](units.md) as something special, they are similar `filters` for the UNIT `topic`.
