# Census Data Explorer

The Census Data Helper provides a chatbot, as well as a written guide on how to access and make sense of the Census Data. This guide will also help you learn some basic SQL too.

The database and data have been forked from the [UK Data Service](https://www.ukdataservice.ac.uk/) Infuse2011 table.

If you have any questions feel free contact me via twitter [@mountaincows](https://twitter.com/mountaincows).

## Downloading the data

I have provided a SQL dump of the simplified table which can be downloaded. I would recommend reading the documentation to fully understand what is going on. If you find something on the database that isn't documented, please get in touch.

Due to the size of the SQL Table, we have also released a minifed version of the table. This table **only** includes metadata, meaning you can play around with the different tables and learn how to get the data. Once you're comfortable with this, I'd recommend proceeding to the larger download

Download the minified SQL Dump, [census-data-explorer-simplified.sql.zip](https://mega.nz/#!nTQAxQ6Z!DzPX2lgGlAp3s2v2RQPAcWlo5IVEkmsyMrTzEfTQxBk)

## Connecting to the Database

At Jisc we have created a guest account for user's to access the data free of charge. Guest's will only be able to perform `SELECT` queries. We currently have the data stored in a `MySQL` database with the following credentials:

```yaml
host: localhost:3306
user: root
password: password
```

You will be able to connect to the database using the [MySQL CLI](https://dev.mysql.com/downloads/mysql/) or you can download [MySQL Workbench](https://www.mysql.com/products/workbench/).

## Using SQL
If you have never used SQL before, this is fine. All the queries in this documentation are relatively straight forward. SQL has the benefit of being *human readable*.

If you're interested in learning SQL, W3 Shools has a great [SQL Tutorial](https://www.w3schools.com/sql/default.asp).

If you just want a quick overview, you can view our [Understaind SQL Page](understanding_sql.md).

## Using the SDKs

We provide a JavaScript and Python SDK. They can be found here:

- [Census Data JavaScript SDK](http://google.com) (todo)
- [Census Data Python SDK](http://google.com) (todo)

## APIs

We provide a REST API as well as a GraphQL API, documentation for these can be found here:

- [Census Data REST API](https://github.com/nathansainsbury/census-data-explorer-api) (todo)
- [Census Data GraphQL API](https://github.com/nathansainsbury/census-data-explorer-graphql) (todo)

## Extra Information

In this section you will find information regarding the following:

- [topics](topics.md)
- [filters](filters.md)

It is good to know what these actually are before querying the data.

## Locations

Every piece of census data you will find has some location/location type attached to it, these different types can be found in the [GL_EXTENTS](fields/gl_extents.md) field. If you want to learn more about each field, check out the links below.

- [2000 - **United Kingdom**](locations/2000.md) (todo)
- [2001 - **Great Britain**](locations/2001.md) (todo)
- [2002 - **England and Wales as a single entity**](locations/2002.md) (todo)
- [2003 - **Countries**](locations/2003.md) (todo)
- [2004 - **Regions**](locations/2004.md) (todo)
- [2005 - **Counties**](locations/2005.md) (todo)
- [2006 - **Local Authorities**](locations/2006.md) (todo)
- [2007 - **Wards and Electoral Divisions**](locations/2007.md)
- [2008 - **Middle Super Output Areas & Intermediate Zones**](locations/2008.md)
- [2009 - **Lower Super Output Areas & Data Zones**](locations/2009.md)
- [2010 - **Output Areas and Small Areas**](locations/2010.md)
- [2011 - **Merging Local Authorities**](locations/2011.md)
- [2012 - **Merging Wards & Electoral Division**](locations/2012.md)
- [2013 - **Workplace Zone Layer**](locations/2013.md) (todo)

## Understanding the Tables

The following section will describe the main meta data tables.

- [codelist_combos](tables/codelist_combos.md)
- [codelist_cube_description](tables/codelist_cube_description.md)
- [codelist_def](tables/codelist_def.md)
- [codes](tables/codes.md)
- [cube_description](tables/cube_description.md)
- [cellmaps](tables/cellmaps.md)
- [geocodes_def](tables/geocodes_def.md) (todo)
- [geocodes_relation](tables/geocodes_relation) (todo)
- [geolevels_def](tables/geolevels_def.md) (todo)
- [geolevels_relation](tables/geolevels_relation.md) (todo)

## Field Definitions

In this section you will find information regarding the most important individual `fields`.

- [CLS](fields/cls.md)
- [GL_EXTENTS](fields/gl_extents.md)
- [UNITS](fields/units.md)
- [DKAN_TITLE](fields/dkan_title.md)
- [CL_CODE](fields/cl_code.md)
- [CODES](fields/codes.md)
- [INFUSE_TABLE_NAME](fields/infuse_table_name.md)
- [CELLNAME](fields/cellname.md)
- [IS_ID](fields/is_id.md)
- [NESTED_DESCRP](fields/nested_descrp.md)

## Example Questions

Going through the tables and column definitions individually can be a bit daunting and abstract. It's often easier to learn these things by going through a few examples. Let's start with a few simple ones:

- [How many people are in full-time employment in Wales?](examples/example_1.md) (finish off)
- more to come...

Hopefully after doing the examples above you should have good understanding of how to interact with the 2011 Census Data. If you're still struggling, that's fine, these things can often take a while to get to grips with. Feel free to ask the [Census Data Helper](http://google.com) any questions you have or alternatively drop me a message on twitter [@mountaincows](https://twitter.com/mountaincows).
