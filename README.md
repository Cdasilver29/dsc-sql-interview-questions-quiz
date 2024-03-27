
# SQL Interview Questions  - Quiz


## Introduction

This quiz contains questions on topics you can expect to see in an interview pertaining to SQL and Relational Databases. Some of them are multiple-choice, while some are short answer. For these short answer questions, double-click on the Jupyter Notebook and type your answer below the line. 

## Question 1

What are the 4 main datatypes in SQLite3? Can we use other common types from other kinds of SQL?

Type your answer below this line:
Integer, Real, Text, and Blob. SQL doesn't directly support all data types from other SQL systems, but there might be workarounds or data type mapping depending on the context._______________________________________________________________________________________________________________________________





## Question 2

Explain the relationship between **Primary Keys** and **Foreign Keys**.

Type your answer below this line:
**Primary keys** and **foreign keys** work together to create a well-structured and reliable relational database. They ensure data consistency, enforce relationships between tables, and enable efficient data retrieval and manipulation._______________________________________________________________________________________________________________________________





## Question 3

Explain the different types of relationships entities can have in a SQL database. 

Type your answer below this line:
The different types of relationship entities in SQL are :
<li> One-to-One Relationship; Each record in the first table corresponds to exactly one record in the second table, and vice versa.
<li> One-to-Many Relationship; A record in the first table can have many related records in the second table, but a record in the second table can only have one related record in the first table.
<li> Many-to-One Relationship; Many records in the first table can be related to a single record in the second table.
<li> Many-to-Many Relationship; Each record in the first table can relate to multiple records in the second table, and vice versa._____________________________________________________________________________________________________________________________


## Question 4

Explain the various types of JOINs possible with SQL. 

Type your answer below this line:
<li> INNER JOIN: returns rows from both tables that have matching values in the specified columns.
<li> LEFT JOIN (or LEFT OUTER JOIN):_returns all rows from the left table (first table specified) and matching rows from the right table (second table specified).
<li> RIGHT JOIN (or RIGHT OUTER JOIN): returns all rows from the right table and matching rows from the left table.
<li> FULL JOIN (or FULL OUTER JOIN):_returns all rows from both tables and matches rows from the left table with rows from the right table based on the specified condition.
<li> CROSS JOIN: returns the Cartesian product of the two tables, meaning it combines each row from the first table with every row from the second table.___________________________________________________________________________________________________________________________



## Question 5

Explain the relationship between Aggregate functions and GROUP BY statements.

Type your answer below this line:
GROUP BY organizes the data and Aggregate functions crunch the numbers within each group, providing a concise and informative summary._______________________________________________________________________________________________________________________________



## Question 6

What role do Associative Entities play (JOIN Tables) in many-to-many JOINs?


Type your answer below this line:
Associative Entities are a cornerstone of effective relational database design for modeling many-to-many relationships. They provide a structured and flexible approach to connect data entities and enrich your data model._______________________________________________________________________________________________________________________________



## Summary

In this lesson, we practiced answering open-ended interview questions for SQL and Relational Databases. 
