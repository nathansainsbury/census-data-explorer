# fields/NESTED_DESCRP

The [NESTED_DESCRP](nested_descrp.md) field can be found in the [codes](../tables/codes.md) table and is almost an extens of the DESCRP field.

This fields makes it easier to determine what an actual filter is, rather than the less descriptive, DESCP.

Let's say you did a search for `Full time` or something similar in the `ECOACT` filter, you would be presented with many rows, an example of some are:

|ID|CL_ID|DESCRP|NESTED_DESCRP|
|-|-|-|-|
|577|18|Full-time|Economically active \ Employee \ Full-time|
|2292|18|Full-time|Economically active\ In employment\ Self-employed \ Full-time|

If you were to only look at the DESCRP field, this wouldn't give you enough information. However, the [NESTED_DESCRP](nested_descrp.md) field show the hierarchy and the granularity of the data.