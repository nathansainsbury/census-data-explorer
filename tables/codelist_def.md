# tables/codelist_def

The `codelist_def` table returns information regarding the individual `topics` which are identified via an `ID` and a `MNU`. These `ID` from this table can be used to `JOIN` on the [codes](codes.md) table, with `CLID`

```sql
SELECT ID, NAME, MNU, DESCRIPTION FROM codelist_def WHERE MNU in ('AGE', 'COB', 'HIQUAL', 'UNIT');
```

Which will return the following table.

|ID|NAME|MNU|DESCRIPTION|
|-|-|-|-|
|3|Age|AGE|Age is derived from the date of birth question and is a person"s age at their last birthday, at 27 March 2011. Dates of birth that imply an age over 115 are treated as invalid and the person"s age is imputed. Infants less than one year old are classified as 0 years of age.|
|12|Country of birth|COB|Country of birth is the country in which a person was born. This topic records whether the person was born in or if they were not born in a country. For the full country of birth classification in England and Wales, please see the National Statistics Country Classification.|
|33|Qualification, highest level of|HIQUAL|The highest level of qualification is derived from the question asking people to indicate all types of qualifications held. People were also asked if they held foreign qualifications and to indicate the closest equivalent. There were 12 response options (plus "no qualifications") covering professional and vocational qualifications, and a range of academic qualifications These are combined into five categories for the highest level of qualification, plus a category for no qualifications and one for other qualifications (which includes vocational or work-related qualifications, and for foreign qualifications where an equivalent qualification was not indicated). No Qualifications: No academic or professional qualifications.Level 1 qualifications: 1-4 O Levels/CSE/GCSEs (any grades), Entry Level, Foundation Diploma, NVQ level 1, Foundation GNVQ, Basic/Essential Skills. Level 2 qualifications: 5+ O Level (Passes)/CSEs (Grade 1)/GCSEs (Grades A*-C), School Certificate, 1 A Level/ 2-3 AS Levels/VCEs, Intermediate/Higher Diploma, Welsh Baccalaureate Intermediate Diploma, NVQ level 2, Intermediate GNVQ, City and Guilds Craft, BTEC First/General Diploma, RSA Diploma Apprenticeship. Level 3 qualifications: 2+ A Levels/VCEs, 4+ AS Levels, Higher School Certificate, Progression/Advanced Diploma, Welsh Baccalaureate Advanced Diploma, NVQ Level 3; Advanced GNVQ, City and Guilds Advanced Craft, ONC, OND, BTEC National, RSA Advanced Diploma. Level 4+ qualifications: Degree (for example BA, BSc), Higher Degree (for example MA, PhD, PGCE), NVQ Level 4-5, HNC, HND, RSA Higher Diploma, BTEC Higher level, Foundation degree (NI), Professional qualifications (for example teaching, nursing, accountancy). Other qualifications: Vocational/Work-related Qualifications, Foreign Qualifications (Not stated/ level unknown).|
|68|Unit|UNIT|The unit is for a particular count (e.g. people or households)|

So when we find `CLS = "AGE,COB,HIQUAL,UNIT"` in the [codelist_combos](codelist_combos.md) table we know that the `topic` combination is `Age`, `Country of birth`, `Qualification highest level of` and `UNIT`. This implies that the data related to this [CLS](../columns/cls.md) will likely be in relation to a breakdown of qualifications with relation to the age and country of birth of people (`UNIT`).
