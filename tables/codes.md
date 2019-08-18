# tables/codes
Where the `codelist_def` table describes the `topics`, the `codes` table describes the `filters`. If we have `MNU = "COB"`, we can perform the following query to get the `ID` of the `topic`:
```sql
SELECT ID, MNU FROM codelist_def WHERE MNU = 'COB';
```
Which returns the follow table.

|ID|MNU|
|-|-|
|12|COB|

Using `codelist_def.ID` we can search the `codes` table where `codelist_def.ID = codes.CLID`. To find a list of filters for this filter, we perform the following query:
```sql
SELECT CLID, ID, DESCRP FROM codes WHERE CLID = 12;
```

Which returns the follow table with 352 rows.

|CLID|ID|DESCRP|
|-|-|-|
|12|246|Total: Country of birth|
|12|247|Europe|
|12|248|United Kingdom|
|12|249|England|
|12|250|Northern Ireland|
|...|...|...|
|12|4428|Antarctica, Oceania and Other|