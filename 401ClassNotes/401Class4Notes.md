# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Data Modeling

[nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

- For complex query intensive environments the best type of database is SQL.  The query power in SQL is much stronger than NoSQL for this type of environment.
- For hierarchical data storage the NoSQL database is a better fit since it follows the key-value pair way of storing data.
- SQL scalibility is increasable by increasing the hardware on a single server, this scales vertically.  This could mean increasing the CPU, RAM, SSD to increase the load available to the SQL server.  Whereas the NoSQL database is scaled horizontally.  You can add more servers easily in a NoSQL infastructure to handle larger traffic.

[sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

- An entry in one table being related to MORE THAN ONE other entry in another table is considered a one-to-many relationship.  We relate them as entries that can have many connected entries, such as describing all the workers within a department.
- Prior to designing your relational database, it might be useful to **draw a diagram** of the database tables and their relationships.
- Primary keys uniquely identify each row in a table.  A table typically has one primary key, BUT can have more.  Foreign keys are a column or columns which MATCH a primary key in another table. These two keys are the glue of how we can create a database with connecting information across data.

[sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

- Keywords and parameters are treated differently within SQL syntax. Keywords refer to an individual SQL element whereas parameters are used to exchange data between stored procedures or function.  The keywords allow users to find a singular element of some kind while parameters can call data values based off a stored procedure or function.
- We normalize data by fitting the data into how the table is structured. Schemas are normalized in the way that incoming data will be all identical formatting to fit into the tables to allow for a uniformed setup of the data.
- A one to one relationship can be described as one table being related to one record in another table. So, if I was sitting at a table and my brother was sitting at another table with 3 other people, we would have one to one relationship.  A one to many would be if the same scenario above had my mother, father, and brother sitting at the opposing table.  I would be the one and they would be the many in the relationship. Lastly, a many to many relationship would be if my cousins, aunts, and uncles joined me at my table while my brother, sister, father, and mother were at another table.  We would have a many to many relationship because of how many connections we had between our 2 tables.

## Bookmark

[sequelize api](https://sequelize.org/master/)

## Reflection

- I think I have two major learning goals after reading through the learning objectives.  Firstly, I want to make sure that I am comfortable with all of the CRUD functionality as well as how to set up each different function.  Secondly, understanding how to navigate through an SQL database using commands is going to be difficult based off the short amount that are presented in the reading.  I think that SQL is going to feel very different from the NoSQL databases we have dealt with before.

## Class Notes

## Things I want to know more about
