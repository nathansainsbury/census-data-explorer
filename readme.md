# Census Data Explorer

The Census Data Helper provides a chatbot, as well as a written guide on how to access and make sense of the Census Data. This guide will also help you learn some basic SQL too.

The database and data have been forked from the [UK Data Service](https://www.ukdataservice.ac.uk/) Infuse2011 table.

If you have any questions feel free contact me via twitter [@mountaincows](https://twitter.com/mountaincows).

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

## Field Definitions

In this section you will find information regarding individual `fields`.

- [CLS](fields/cls.md)
- [GL_EXTENTS](fields/gl_extents.md)
- [UNITS](fields/units.md)
- [DKAN_TITLE](fields/dkan_title.md)
- [CL_CODE](fields/cl_code.md)
- [CODES](fields/codes.md)
- [INFUSE_TABLE_NAME](fields/infuse_table_name.md)
- [CELLNAME](fields/cellname.md)

To do:
- [IS_ID](fields/is_id.md)

## Example Questions

Going through the tables and column definitions individually can be a bit daunting and abstract. It's often easier to learn these things by going through a few examples. Let's start with a few simple ones:

- [How many people are in full-time employment in Wales?](examples/example_1.md)
- [How many Sikh's are working in England and Wales (combined)?](examples/example_2.md)

Hopefully after doing the examples above you should have good understanding of how to interact with the 2011 Census Data. If you're still struggling, that's fine, these things can often take a while to get to grips with. Feel free to ask the [Census Data Helper]() any questions you have or alternatively drop me a message on twitter [@mountaincows](https://twitter.com/mountaincows).
