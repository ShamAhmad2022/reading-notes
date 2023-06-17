# Data Modeling

It's really very important for me to know more about databases and the difference between SQL and NoSQL because it will help me decide which one i should use based on the project i want to work on. beside of course it is an important topic i should professionalize as a fullstack developer

## nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?
    
    A: SQL

2. What type of database is the best fit for hierarchical data storage?

    A: NoSQL

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

    A: SQL scales vertically, that's mean improving the server capacity by increaseing the CPU, RAM  and SSD, because for the data in SQL sometimes it's hard to be splited disturbed, unlike the NoSQL, which scales horizontally by adding more servers, and split the data on the servers.

## sql modeling techniques

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?
    
    A: An entry in one table can be related to more than an entry, and we can relate them using notations 
    
2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

    A: create, diagram

3. Explain the difference between a primary and foreign key.

    A: Primary key is used to uniquely identify each row in the table, whereas a foreign key is a reference to match a primary key in another table.

## sql vs nosql

1. How do we treat keywords and parameters differently in SQL syntax?
    
    A: keywords are reserved words that have a specific meaning and cannot be used as identifiers such as table names or column names, whereas Parameters are the user-supplied values

2. Define normalization within the context of schemas and data.

    A: normalization is a way to ensure that the data format is fit to the schema in the table

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

    A: 
    * one-to-one: an entity can be related with only another one entity, like when every citizen has one unique ID number
    * one-to-many: an entity can be related with with more than one entity, like customers and orders, whereas every customer can have many orders, the order can be specified with one user
    * many-to-many: a group of entities can be related with another group of entities, like students and courses, a students may enroll in many courses and the courses can have many students 

## Things I want to know more about

All the necessary things has to do with the database