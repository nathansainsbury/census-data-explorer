# Census Data Helper

The Census Data Helper provides a chatbot, as well as a written guide on how to access and make sense of the Census Data. This guide will also help you learn some basic SQL too.

The database and data have been forked from the [UK Data Service](https://www.ukdataservice.ac.uk/) Infuse2011 table.

If you have any questions feel free contact me via twitter [@mountaincows](https://twitter.com/mountaincows).

## Connecting to the Database

At Jisc we have created a guest account for user's to access the data free of charge. Guest's will only be able to perform `SELECT` queries. We currently have the data stored in a `MySQL` database with the following credentials:

```yaml
host: unknowhost.com:3306
user: guest
password: password
```

You will be able to connect to the database using the [MySQL CLI](https://dev.mysql.com/downloads/mysql/) or you can download [MySQL Workbench](https://www.mysql.com/products/workbench/).

## Using SQL
If you have never used SQL before, this is fine. All the queries in this documentation are relatively straight forward. SQL has the benefit of being *human readable*.

If you're interested in learning SQL, W3 Shools has a great [SQL Tutorial](https://www.w3schools.com/sql/default.asp).

If you just want a quick overview, you can view our [Understaind SQL Page](understanding_sql.md).

## Using the SDKs

We provide a JavaScript and Python SDK. They can be found here:

- [Census Data JavaScript SDK](http://google.com)
- [Census Data Python SDK](http://google.com)

## APIs

We provide a REST API as well as a GraphQL API, documentation for these can be found here:

- [Census Data REST API](https://github.com/nathansainsbury/census-data-explorer-rest-api)
- [Census Data GraphQL API](https://github.com/nathansainsbury/census-data-explorer-graphql-api)

## Understanding the Tables
The following section will describe the main meta data tables.

- [codelist_combos](tables/codelist_combos.md)
- [codelist_cube_description](tables/codelist_cube_description.md)
- [codelist_def](tables/codelist_def.md)
- [codes](tables/codes.md)
- [cube_description](tables/cube_description.md)

## Column Definitions

In this section you will find information regarding individual column `defintions/fieilds`.

- [CB_ID](columns/cb_id.md)
- [CLS](columns/cls.md) (complete)
- [GL_EXTENTS](columns/gl_extents.md)
- [EXTENTS_DETAILS](columns/extents_details.md)
- [UNITS](columns/units.md)
- [DKAN_TITLE](columns/dkan_title.md)
