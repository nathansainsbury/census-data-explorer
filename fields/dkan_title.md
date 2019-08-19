# fields/DKAN_TITLE

The [DKAN_TITLE](dkan_title.md) field describes a given [CLS](cls.md) field. The main difference between them is that the [DKAN_TITLE](dkan_title.md) field is human-readable and for use in a front-end.

```sql
SELECT CB_ID, CLS, DKAN_TITLE FROM codelist_comboes;
```

|CB_ID|CLS|DKAN_TITLE|
|-|-|-|
|98|AGE, COB, HIQUAL, UNIT|Age by Country of birth by Highest level of qualification 2011|
|99|AGE, COB, MNLANNI, UNIT|Country of birth by Main language (Northern Ireland) 2011|
|100|AGE, COB, PCOMST, UNIT, URESPOP|Age by Country of birth (Communal establishment residents) 2011|
|...|...|...|
|733|DPCHDF, FAMSTA, PRUNCA, UNIT, URESPOP|Dependent children in family by Family status by Provision of unpaid care 2011|
|734|DPCHDR, FAMSTA, UNIT|Dependent children in family by Family status 2011|
|735|DPCHDF, FAMSTA, UNIT, URESPOP|Dependent children in family by Family status by Usual resident population 2011|
|...|...|...|
