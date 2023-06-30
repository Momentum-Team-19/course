---
title: Databases
category: python
parent: References
layout: resource_list
---

{% include summary_toc.html %}

### Database GUIs

- [DB Browser for SQLite](https://sqlitebrowser.org/)
- [Postico for Postgres](https://eggerapps.at/postico/)
- [DBeaver - Universal Database Tool](https://dbeaver.io/) - This is much more complex than you may need but it is interesting.

### Advanced Databases

- 📖 [Full Stack Python: Databases](https://www.fullstackpython.com/databases.html)
- 📖 [Full Stack Python: ORMs](https://www.fullstackpython.com/object-relational-mappers-orms.html)
- [What is a relational database?](https://www.techtarget.com/searchdatamanagement/definition/relational-database)
- 📖 [Writing Safe Database Migrations in Django](https://markusholtermann.eu/2021/06/writing-safe-database-migrations-in-django/)
- [Using Postgres Locally](https://momentumlearn.notion.site/Using-Postgres-Locally-6d24cd1ea8854eabb875023d6696fba9)
- [Digging Deeper Into Migrations](https://realpython.com/digging-deeper-into-migrations/)

### Data Modeling

- [Class-Responsibility-Collaborator Model (CRC)](http://agilemodeling.com/artifacts/crcModel.htm)
- [Entity Relationship Diagrams (ERD), from Lucid Chart](https://www.youtube.com/watch?v=QpdhBUYk7Kk)
- [What is an Entity Relationship Diagram?](https://www.lucidchart.com/pages/er-diagrams) - _The first video is especially good._
- [Database Design Tutorial](https://learndjango.com/tutorials/database-design-tutorial-beginners) _This is a great short article that is really an intro to databases. It covers some data best practices and explains primary keys, foreign keys, and relationships._

### Database Normalization

This is very much optional at this early stage of your learning but important to learn about at some point if you're going to be working with data in your job.

- [An Introduction to Database Normalization](http://mikehillyer.com/articles/an-introduction-to-database-normalization/)
- [Video on the first normal form](https://youtu.be/K7vzLrGCV50)
- [Video on the second normal form](https://youtu.be/A9sezRxNhWY)
- [Video on the third normal form](https://youtu.be/GP_RcibUicQ)

#### Databases and SQL

Confidence working with the database is important for back end devs, so it's worth taking the time to really understand how they work.

We don't need to write SQL when we are using an ORM, but it's still a skill that is very useful for back-end work.

- [Full Stack Python: Databases](https://www.fullstackpython.com/databases.html)
- [SQL Basics: Learn x in y minutes](https://learnxinyminutes.com/docs/sql/) This may be helpful to skim for familiarity with SQL when you see it. You do not need to write SQL because the Django ORM does it for you, and it does it well. Most developers _can_ drop into SQL if they need to work with the database directly (and they know how to look up the syntax they need!).
- [Learn SQL on Khan Academy](https://www.khanacademy.org/computing/computer-programming/sql)
- [SQL Basics Reference](https://hunter-ducharme.gitbook.io/sql-basics/)
- [How SQL queries run](https://jvns.ca/blog/2019/10/03/sql-queries-don-t-start-with-select/) The syntax for SQL queries can be confusing. It can help to understand the order of operations in which your query will run. This is a blog post from the fantastic Julia Evans breaking it down for you.
    - [In tweet form for quick reference](https://twitter.com/b0rk/status/1179449535938076673)
