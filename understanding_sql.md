# Understanding SQL

Imagine a `table` as an Excel Sheet, like this one below.

![Excel Example 1](https://i.imgur.com/4uGC1MU.png)

In this `table` (let's call it **example**) we have `headers/column names`, `rows` and `fields`. Let's say we wanted to `SELECT` the `row` where `ID = 2`, without doing any `SQL` queries, we can clearly see that we are looking for `row` 3. If we wanted to find this row using `SQL` we could perform the following query:

```sql
SELECT * FROM example WHERE ID = 2;
```

All this query means is: find me all rows from the **example** table where ID is equal to 2, and show me all the column headers. The `SELECT *` means that we want all the `headers`. This example query would return:

![Excel Example 2](https://i.imgur.com/rZx89mP.png)

If we were only interested in finding the `FORENAME` and `SURNAME` of this person, we would perform the following query:

```sql
SELECT FORENAME, SURNAME FROM example WHERE ID = 2;
```
![Excel Example 3](https://i.imgur.com/6Imotnc.png)

This is just a very basic overview of how `SELECT` queries work. There is a lot more to know, so I would recommend reading the [W3 Schools SQL Guide](https://www.w3schools.com/sql/default.asp).