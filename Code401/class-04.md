## Reading Notes
## Assignment: Data Modeling

Statement: This topic is important because...
___

### Questions:
___


[nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

1.  What type of database is the best fit for the complex query intensive environment?
	- SQL
2.  What type of database is the best fit for hierarchical data storage?
	- NoSQL
3.  Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
	- sql databases are more reliant on hardware to scale, whereas nosql just needs more raw space, not much computing power.

[sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

1.  Among data tables, what is a one-to-many relationship and how do we “relate” them?
	- a one to many relationship is a table links to many other tables (with keys)
2.  Prior to designing your relational database, it might be useful to **__**_ a **__**_ of the database tables and their relationships.
	- diagram
3.  Explain the difference between a primary and foreign key.
	- a primary key is an indentifier for the entry itself whereas a foreign key links back to a primary key to relate them.

## Videos

[sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

1.  How do we treat keywords and parameters differently in SQL syntax?
	- SQL is a language and likewise SQL DB have the exact same syntax. NoSQL have many differences but the terminology is still the same usually.
2.  Define normalization within the context of schemas and data.
	- normalization is used to avoid data redundancy, and that all data has its own location and not just one giant table
3.  Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
	- one to many: one table has more than one subtables. ex customer has address, contact info
	- one to one: a user has their demographic info linked to just contact info
	- many to many: you have orders placed by multiple different customers who have multiple tables of information with their own set of keys.


## Bookmark and Review

[sequelize api](https://sequelize.org/master/)


### Things I want to know more about:
___


### Sources (if any):
___
