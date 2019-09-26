Hadoop is an Apache open-source that store and proccess Big Data.   
Provides: parallel computation
In Apache Hadoop you can do queries in a greater scale at lower cost.

Apache Sqoop is a tool that transfers structured data from a RDBMS to HDFS, preserving the structure. When we use this it is launching MapReduce jobs to pull the data from our MySQL database and write the data to HDFS in parallel, distributed across the cluster in Apache Parquet format (format designed for analytical applications on Hadoop. Instead of grouping your data into rows like typical data formats, it groups your data into columns.). 

Hive was designed to interact with data stored in HDFS (Hadoop Distribution File System). Hive is similar to SQL but is called HiveQL or HQL. Impala also is use to query the data the diference is that HUE have a web-base interface