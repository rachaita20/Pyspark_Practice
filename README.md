### What is Apache Spark™?
[Apache Spark™](https://spark.apache.org/) is an open-source, distributed computing system designed for fast and flexible large-scale data processing. It provides a unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning, and graph processing. Here are some key features and components of Apache Spark:

### Key Features
1. Speed:
    - Spark is known for its in-memory computing capabilities, which makes it much faster than traditional disk-based processing frameworks like Hadoop MapReduce. It can perform data processing tasks up to 100 times faster.
    
2. Ease of Use:
    - Spark provides simple and expressive APIs for various languages, including Python, Scala, Java, and R. This makes it accessible to a wide range of developers and data scientists.
    
3. Advanced Analytics:
    - Spark supports a wide range of advanced analytics, including SQL queries, machine learning, streaming data, and graph processing.

4. Unified Engine:
    - Spark can handle diverse data processing tasks through its unified engine, which simplifies development and deployment of data processing applications.

5. Scalability:
    - Spark can scale from a single server to thousands of machines, making it suitable for both small-scale and large-scale data processing tasks.

### Components of Apache Spark
1. Spark Core:
    - The foundation of Spark, Spark Core provides basic functionalities such as task scheduling, memory management, fault recovery, and storage system interactions. It also includes the APIs for defining and manipulating distributed collections of data (RDDs).

2. Spark SQL:
    - A module for working with structured data, Spark SQL provides a programming interface for working with DataFrames and the ability to execute SQL queries. It integrates with existing data sources such as Hive, Avro, Parquet, ORC, and JSON.

3. Spark Streaming:
    - This component enables processing of real-time data streams, allowing for continuous stream processing. It supports sources like Kafka, Flume, and Kinesis, and can run alongside batch processing.

4. MLlib (Machine Learning Library):
    - A scalable machine learning library that provides common machine learning algorithms, including classification, regression, clustering, collaborative filtering, and dimensionality reduction. It also includes utilities for model evaluation and data preprocessing.
    
5. GraphX:
    - A graph processing framework within Spark that allows for the analysis and computation of graphs and graph-parallel computations. It includes tools for creating, manipulating, and querying graphs.

### Common Use Cases
Data Processing, Data Analysis, Machine Learning, Real-Time Data Processing, Graph Computation

### What is PySpark?
[PySpark](https://spark.apache.org/docs/latest/api/python/index.html) is the Python API for Apache Spark. It allows Python developers to harness the power of Apache Spark's distributed computing capabilities through a Python-friendly interface. PySpark enables users to perform large-scale data processing, machine learning, and real-time stream processing using Python.


## Pre-requisites
1. Install PySpark
   ```
   pip install pyspark
   ```
2. [Install Java for mac](https://www.java.com/en/download/)
   

