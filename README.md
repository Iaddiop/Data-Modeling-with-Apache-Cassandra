# Data Modeling with Apache Cassandra
In this project, we will explain how to load CSV files to a [Cassandra database](https://cassandra.apache.org/_/index.html). The DB is about the informations, collected on songs user activity on their new music streaming app called Sparkify. We will be use python programming language to achieve this project.
The CSV files are stored on a directory as event files.
The database will be used later on analytical dashboards (marketing, financial ...) to understand user behavior and usage habits.

Different steps will be taken to modeling the NoSQL database on Apache Cassandra :
- Part 1 : data Pre-Processing
    - Navigate in the path to retrive the data
    - Create a csv that will be use to insert data in Cassandra database ans tables
- Part 2 : build ETL to 
    - Create tables (each table will be response to an especific select query of ower data)
    - Insert rows in the tables
- Testing the return of the select statements

# About the data :
The data stored in :
[event_data]()

# Data modeling :
The data will be disign like this :
- All tables will be creted base on query that we want to execute
- Then we writ the keyspace and set it
- Crete tables depending on the queries and set the primary keys based on the queries

# To run this project :

# References :
- Apache cassandra : https://cassandra.apache.org/_/index.html