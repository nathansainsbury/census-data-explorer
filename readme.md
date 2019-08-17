# Census Data Helper

The Census Data Helper provides a chatbot, as well as a written guide on how to access and make sense of the Census Data. This guide will also help you learn some basic SQL too.

## Connecting to the Database
At Jisc we have created a guest account for user's to access the data free of charge. Guest's will only be able to perform `SELECT` queries. We currently have the data stored in a `MySQL` database with the following credentials:

```yaml
host: unknowhost.com:3306

user: guest

password: password
```

You will be able to connect to the database using the [MySQL CLI](https://dev.mysql.com/downloads/mysql/) or you can download [MySQL Workbench](https://www.mysql.com/products/workbench/).

## Using the SDKs

We provide a JavaScript and Python SDK. They can be found here:
- [Census Data JavaScript SDK](http://google.com)
- [Census Data Python SDK](http://google.com)

## Understanding the Tables
The following section will describe the main meta data tables.

### codelist_combos

The `codelist_combos` table contains information regarding the different possibilities of `codes` as well as the `locations` where these are available. To start with, we'll do a simple `SELECT` query:

```sql
SELECT CB_ID, CLS, GL_EXTENTS, GLIST_DETAILS, EXTENTS_DETAILS, UNITS, DKAN_TITLE FROM codelist_combos WHERE CB_ID IN (98, 326, 403);
```

This query will return the following table.

|CB_ID|CLS|GL_EXTENTS|GLIST_DETAILS|EXTENTS_DETAILS|UNITS|DKAN_TITLE|
|-|-|-|-|-|-|-|
|98|AGE, COB, HIQUAL, UNIT|2002:3, 2003:4, 2003:7, 2004:4, 2005:4, 2006:4, 2006:7, 2007:4, 2007:7, 2008:4, 2008:7, 2009:4, 2009:7, 2010:4, 2010:7, 2011:4, 2012:4, 2012:7|2002, 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011, 2012|3, 4, 7|1962|Age by Country of birth by Highest level of qualification 2011|
|326|AGE, ETHGRNI, GENHEA, LLHPDI, UNIT|2003:5|2003|5|1962|Age by Ethnic group in Northern Ireland by General health by Long-term health problem or disability 2011|
|403|AGE, HIGQUAL, OOTT, UNIT|2002:3, 2003:4, 2003:7, 2004:4, 2005:4, 2006:7, 2007:4, 2007:7, 2008:4, 2009:4, 2009:7, 2010:4, 2010: 7, 2011:4, 2012:4, 2012:7|2002, 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011, 2012|3, 4, 7|1962|Highest level of qualification (Out of term-time population) 2011|

Currently, this data won't mean much without understanding the column names and definitions. These are explained in the [column names](##Column-Definitions) section, more specifically you can find the specific column you're looking for by clicking any of the links below:

- [CB_ID](###CB_ID)
- [CLS](###CLS)
- [GL_EXTENTS](###GL_EXTENTS)
- [EXTENTS_DETAILS](###EXTENTS_DETAILS)
- [UNITS](###UNITS)
- [DKAN_TITLE](###DKAN_TITLE)

In summary, this tells you the possible combinations of `filters`, `topics` and `locations`.

### **codelist_cube_description**

### **codelist_def**

The `codelist_def` table returns information regarding the individual `topics` which are identified via an `ID` and a `MNU`. These `ID` from this table can be used to `JOIN` on the `codes` table, with `CLID`

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
### **codes**

### **cube_description**

## Column Definitions

In this section you will find information regarding individual column `defintions/fieilds`.

### **CB_ID**

### **CLS**

The CLS column refers to data which takes a format like:

|CLS|
|-|
|AGE, COB, HIQUAL, UNIT|
|AGE, ETHGRNI, GENHEA, LLHPDI, UNIT|
|AGE, HIQUAL, OOTT, UNIT|

The CLS is essentially a combination of `topics`, sometimes refered to as `MNU`. What the first row means that the topics `AGE`, `COB`, `HIQUAL` and `UNIT` exist as a combination for given `filters` and `locations`.

For a brief description of what this combination means, you can look at the [DKAN_TITLE](###DKAN_TITLE), which in this case is:

> Age by Country of birth by Highest level of qualification 2011

You can also use the [codelist_def](###codelist_def) table to find out what the indvidiiaul `topics/MNUs` stand for.
### **GL_EXTENTS**

### **EXTENTS_DETAILS**

### **UNITS**

### **DKAN_TITLE**