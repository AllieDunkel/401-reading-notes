# Reading

## nosql vs sql

What type of database is the best fit for the complex query intensive environment?
SQL databases

What type of database is the best fit for hierarchical data storage?
NoSQL

Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.

## sql modeling techniques

Among data tables, what is a one-to-many relationship and how do we “relate” them?
We connect lines between tables to show relationships.  In some cases an entry in one table can be related to more than one entry in another.  This is called a one-to-many relationship.  

Prior to designing your relational database, it might be useful to create a diagram of the database tables and their relationships.

Explain the difference between a primary and foreign key.
primary keys uniquely identify each row in a table and the foreign key column or set of columns which match a primary key in another table.

## sql vs nosql

How do we treat keywords and parameters differently in SQL syntax?


Define normalization within the context of schemas and data.
The goal of normalized schemas is to avoid storage of duplicate data so that stored data can't become inconsistent. 

Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
One-to-one: A record in one table is related to one record in another table. 

One-to-many: A record in one table is related to many records in another table. 

Many-to-many: Multiple records in one table are related to multiple records in another table.
