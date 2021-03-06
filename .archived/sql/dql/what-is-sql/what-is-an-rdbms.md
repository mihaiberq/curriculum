---
author: nickdaminov

levels:

  - beginner

  - basic

type: normal

category: must-know

inAlgoPool: false

tags:
  - introduction

aspects:
  - introduction

standards:
  sql.connect-client.0: 10

links:

  - '[What is Relational Database?](http://searchsqlserver.techtarget.com/definition/relational-database){website}'
  - '[What is RDBMS?](http://searchsqlserver.techtarget.com/definition/relational-database-management-system){website}'

---

# What is an RDBMS?

---
## Content

*RDBMS* stands for **Relational Database Management System**. 

*Relational Databases* store data in *tables*, which are similar to a spreadsheet in that they've got rows and columns. 

When you want data in one _table_ to reference data in another _table_, you create a _relation_ between them. 

A Relational Database Management System is therefore the program that actually does the creating, reading, updating, searching, filtering, and relating. It does this using a Structured Query Language called SQL.

SQL has three main elements:

1. **DDL**, which stands for **Data Definition Language**. This is how we define the data that the tables contain. The DDL commands are executed on the **Database Server**, and the database server creates space for it.

2. **DML**, which stands for **Data Modification Language**. This is how we insert new information in the database, or how we alter the already existing data.

3. **DQL**, which stands for **Data Query Language**, and is how we retrieve data from a database. With DQL, we write commands that query from the **Database Client** and return the requested information. One simple example of DQL is returning all rows and columns from a table, and is done using this syntax:

```sql
SELECT * FROM users;
```

---
## Practice

What do DDL and DQL stand for?

DDL = ???
DQL = ???

* Data Definition Language
* Data Query Language
* Database Definition Language
* Database Query Language
* Duck Definition Language
* Duck Query Language

---
## Revision

How do you think we could create a table called `coupons`?

```sql
??? (
  id INT,
  name VARCHAR(500),
  cost FLOAT
);
```

* `CREATE TABLE coupons`
* `MAKE TABLE coupons`
* `rdbms.createTable('coupons')`
* `sql.create.table('coupons')`
 
 
 
