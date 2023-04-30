# Interactive_SQL_with_pyspark
This project aims to build an Interactive SQL with PySpark that takes input values from users and performs SQL queries in Spark using Google Colab. The users do not need to enter the query by themselves.

Spark is a powerful open-source data processing engine that can process data from various data sources such as Hadoop Distributed File System (HDFS), Apache Cassandra, and Amazon S3. PySpark is the Python API for Apache Spark, which is a distributed computing system designed to process large datasets in a scalable and efficient way. SQL, or Structured Query Language, is a programming language that is used to manage and manipulate relational databases. Google Colaboratory, is a cloud-based platform that allows users to write, run, and share Python code online without having worry about configurations much. User functions will be built in Python that performs SQL queries in PySpark. This will make it easier for users with little or no knowledge of SQL query formats. The project also aims to create an interactive SQL server that is connected to Google Colab notebook and let the users play with the databases and tables they have created.

Table of file contents:

1.	Interactive_SQL_spark1.ipynb: 

this contains the code of “Interactive SQL with PySpark” it gets the input from the user and perform operations based on user’s input. This code will run on Google Colab. In Google Colab, please run the code cell by cell, first cell contains ‘pip install pyspark’ which will install pyspark in google colab, after that we can perform operations.

2.	Pyspark_SQL_server2.ipynb: 

this contains the code of “Interactive SQL with PySpark” , but with an extension where I tried to connect pyspark to SQL server. Please run the code cell by cell in Google Colab, first cell contains ‘pip install pyspark’ which will install pyspark in google colab, after that we can perform operations. Although I am getting error related to JDBC driver.

3.	Project report : 

The attached project report provides a detailed overview of the technologies utilized, the objectives pursued, and the methodologies applied throughout the project, with the aim of documenting the project's key activities and outcomes.(along with snapshots of the code working, some outputs).

Google Colab instructions: please upload the ‘.ipynb’ files to Google Colab and run cell by cell. It will work.
