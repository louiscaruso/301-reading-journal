- Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database

- To retrieve data from a SQL database, we need to write SELECT statements, which are often referred to as queries

- SQL doesn't require you to write the keywords all capitalized, but it helps people distinguish SQL keywords from column and tables names, and makes the query easier to read

- The WHERE clause is applied to each row of data by checking specific column values to determine whether it should be included in the results or not

```Select Query With Retraints

SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;
```
    
## SQL Commands Classification
- Data Definition Language (DDL) : CREATE TABLE, ALTER TABLE, DROP TABLE etc. These commands allow you to create or modify your database structure.

- Data Manipulation Language (DML) : INSERT, UPDATE, DELETE These commands are used to manipulate data stored inside your database.

- Data Query Language (DQL) : SELECT Used for querying or selecting a subset of data from a database.

- Data Control Language (DCL) : GRANT, REVOKE etc. Used for controlling access to data within a database, commonly used for granting user privileges.

- Transaction Control Commands : COMMIT, ROLLBACK etc. Used for managing groups of statements as a unit of work.