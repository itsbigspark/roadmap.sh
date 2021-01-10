# Becoming a Data Engineer


## What does a Data Engineer do?

In short, data engineers are responsible for designing, developing, and maintaining the data platform, which includes the data infrastructure, data applications, data warehouse, and data pipelines.

In a big company, data engineers are usually divided into different groups that work with a specific part of the data platform:

-   **Data warehouse & pipelines**: Data warehouse engineers build batch and/or real-time data pipelines to integrate data between systems and support the [data warehouse](https://en.wikipedia.org/wiki/Data_warehouse). Since the data warehouse is meant for tackling business problems, data warehouse engineers usually work closely with data analysts, scientists, or business teams that serve a specific business function.
-   **Data infrastructure**: Data infrastructure engineers build and maintain the very foundation of a data platform: the distributed systems that everything runs on top of. For example, at Target, the data infra team maintains [Hadoop](https://hadoop.apache.org/) clusters used by the whole enterprise.
-   **Data applications**: Data application engineers are software engineers building internal data tools and APIs. Sometimes, a great internal tool may later become an open-source product of the company. For example, one of the data product teams at Lyft built a data discovery tool called [Amundsen](https://github.com/lyft/amundsen), which was open-sourced in 2019.  



## Basic, fundamental skills for everything

- **Version Control Systems and Git:** version control systems allow you to track changes to your codebase/files over time.

- **Shell scripting/bash:** used on a large scale for task scheduling, automation and file management

- **SSH:** remote access to servers

- **HTTP/HTTPS:** firm grasp of  transfer protocols and certificates, as you will use this knowledge it when you need to get data from APIs 

- **SQL:** used in absolutely every step

- **CI/CD:** required for creating automated build and testing pipelines for code

- **Containerisation / Docker :** for orchestration your containers

- **IaC/IaaS:** infrastructure and service is code now

  

## Programming Languages and Data

Programming aptitude is required for meaningful use of open source libraries.   The major languages to 

- Python
- Java
- Scala
  

## Concepts

Some important concepts about data modelling, analytical repositories and big data

- **Storage formats:**  Parquet, Avro, ORC, Protobuf

- **Query/process optimisation :** Partitioning, bucketing, hashing, caching

- Star Schema

- Data Warehouses

- Data Lakes

- Data Catalog

- Data Lineage

- Data Pipelines


  
## Databases

Knowledge of databases guides you to choose the best for your Big Data project, considering which one is best suited in each scenario.

- RDBMS

- Document DB

- In-Memory DB

  

## ETL and ELT

ETL and ELT are two of the most popular methods of collecting data from multiple sources and storing it in a data warehouse that can be accessed by all users in an enterprise

- Apache Airflow

- Apache Nifi

- Pentaho

  

## Data Processing

Parallel processing of big data was first realised by data partitioning technique in database systems and ETL tools. Once a dataset is partitioned logically, each partition can be processed in parallel.

- Apache Kafka

- Apache Hadoop

- Apache Spark

