# Data Modeling with Apache Cassandra
In this project, we will explain how to load CSV files to a [Cassandra database](https://cassandra.apache.org/_/index.html). The DB is about the informations, collected on songs user activity on their new music streaming app called Sparkify. We will be use python programming language to achieve this project.
The CSV files are stored on a directory as event files.
The database will be used later on analytical dashboards (marketing, financial ...) to understand user behavior and usage habits.

Different steps will be taken to modeling the NoSQL database on Apache Cassandra :
- Part 1 : ETL pipepline to Pre-Processing data
    - Navigate in the path to retrive the data
    - ETL to create a csv that will be use to insert data in Cassandra database ans tables
- Part 2 : data modeling with Cassandra 
    - Create tables (each table will be response to an especific select query of ower data)
    - Insert rows in the tables
    - Testing the return of the select statements 

# About the data :

# Data modeling :
The data will be disign like this :
- Specify the keyspace and set it
- Create All tables based on the query that we want to execute or the informations that we want to retrieve
- Create for each table a composite key

# Composition of the project :
- The data stored in : [event_data](https://github.com/Iaddiop/Data-Modeling-with-Apache-Cassandra/blob/master/data_download.zip)
- The Notebook : [Project_1B_ Project_Template.ipynb](https://github.com/Iaddiop/Data-Modeling-with-Apache-Cassandra/blob/master/Project_1B_%20Project_Template.ipynb)
- The file [event_datafile_new.csv](https://github.com/Iaddiop/Data-Modeling-with-Apache-Cassandra/blob/master/event_datafile_new.csv) will be store all events after the part 1 : data pre_processing
# References :
- [Apache cassandra](https://cassandra.apache.org/_/index.html)
- [Designing a Cassandra Data Model](https://shermandigital.com/blog/designing-a-cassandra-data-model/)
- [StackOverflow thread to understand difference between partition key, composite key, and clustering column](https://stackoverflow.com/questions/24949676/difference-between-partition-key-composite-key-and-clustering-key-in-cassandra/24953331#24953331)