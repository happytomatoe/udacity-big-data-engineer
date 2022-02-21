# Data Engineering Nanodegree
---

All projects of Udacity's Data Engineering Nanodegree.

[Course page](https://www.udacity.com/course/data-engineer-nanodegree--nd027)
<br><br>
Educational Objectives: Student learns to
- Create user-friendly relational and NoSQL data models
- Create scalable and efficient data warehouses
- Work efficiently with massive datasets
- Build and interact with a cloud-based data lake
- Automate and monitor data pipelines
- Develop proficiency in Spark, Airflow, and AWS tools

> Python, Postgres, Casandra, Redshift, Apache Spark, Airflow, Database modelling, Dimensional modelling, ETL

## Certificate

<img src="./docs/udacity-dend-cert.svg" alt="certificate" style="zoom:50%;" />

## About The Nanodegree

## Program details

#### **Course 1 – Data Modeling**
Key takeaways:
- Understand the purpose of data modeling
- Identify the strengths and weaknesses of different types
of databases and data storage techniques
- Create a table in Postgres and Apache Cassandra
- Understand when to use a relational database
- Understand the difference between OLAP and OLTP
databases
- Create normalized data tables
- Implement denormalized schemas (e.g. STAR, Snowflake)
- Understand when to use NoSQL databases and how
they differ from relational databases
- Select the appropriate primary key and clustering
columns for a given use case
- Create a NoSQL database in Apache Cassandra

Related projects:
- ##### [Data Modeling with Postgres](https://github.com/happytomatoe/data-modeling-with-postgres)
In this project, I modeled user activity data for a music streaming
app called Sparkify. I created a relational database and ETL
pipeline designed to optimize queries for understanding what songs
users are listening to. In PostgreSQL I also defined Fact and
Dimension tables and insert data into your new tables.
- ##### [Data Modeling with Apache Cassandra](https://github.com/happytomatoe/data-modeling-with-cassandra)
In these projects, I modelel user activity data for a music
streaming app called Sparkify. I created a database and ETL
pipeline, in both Postgres and Apache Cassandra, designed to
optimize queries for understanding what songs users are listening
to. For PostgreSQL, I also defined Fact and Dimension tables
and inserted data into your new tables. For Apache Cassandra, I
modeled the data so  the
analytics team at Sparkify can run specified queries.

#### **Course 2 – Cloud Data Warehouses**
Key takeaways:
- Understand Data Warehousing architecture
- Run an ETL process to denormalize a database (3NF to Star)
- Create an OLAP cube from facts and dimensions
- Compare columnar vs. row oriented approaches
- Set up Amazon S3, IAM, VPC, EC2, RDS PostgreSQL
- Identify components of the Redshift architecture
- Run ETL process to extract data from S3 into Redshift
- Set up AWS infrastructure using Infrastructure as Code
  (IaC)
- Design an optimized table by selecting the appropriate
  distribution style and sorting key

- #####  [Cloud Data Warehouse project](https://github.com/happytomatoe/data-modeling-with-redshift)
In this project, I built an ELT pipeline that
extracts their data from S3, stages them in Redshift, and transforms
data into a set of dimensional tables for the analytics team to
continue finding insights in what songs their users are listening to.

#### **Course 3 – Data Lakes with Apache Spark**
Key takeaways:
- Understand the big data ecosystem
- Understand when to use Spark and when not to use it
- Manipulate data with SparkSQL and Spark Dataframes
- Use Spark for ETL purposes
- Troubleshoot common errors and optimize their code using
  the Spark WebUI
- Understand the purpose and evolution of data lakes

##### [Data lake project](https://github.com/happytomatoe/data-lake)
In this project, I built an ETL pipeline for a data lake. The data
resides in S3, in a directory of JSON logs on user activity on the app,
as well as a directory with JSON metadata on the songs in the app.
I loaded data from S3, processed the data into analytics tables
using Spark, and loaded them back into S3.

#### **Course 4 – Data Pipelines with Apache Airflow**
Key takeaways:
- Create data pipelines with Apache Airflow
- Set up task dependencies
- Create data connections using hooks
- Track data lineage
- Set up data pipeline schedules
- Partition data to optimize pipelines
- Write tests to ensure data quality
- Backfill data
- Build reusable and maintainable pipelines
- Build your own Apache Airflow plugins
- Implement subDAGs
- Set up task boundaries
- Monitor data pipelines


#### [Data Pipelines with Airflow project](https://github.com/happytomatoe/data-pipelines-with-airflow)
In this project, I continued working on the music streaming
company’s data infrastructure by creating and automating a set of
data pipelines. I configured and scheduled data pipelines with
Airflow and monitored and debugged production pipelines.

#### **Capstone Project**
#### [Yelp ETL pipeline project](https://github.com/happytomatoe/yelp-etl-pipeline)
In this project I transformed initial data into dimensional model using star schema and export it into redshift. 
To show results I made exploratory data analysis