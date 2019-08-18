# tables/codelist_combos

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
