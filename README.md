# Amazon Product Analysis with PySpark
We are utilizing Big Data technologies such as the platforms of PySpark and HDFS to perform an analysis of the Amazon Products with Python. PySpark has been used to perform the analysis and HDFS has been used for data storage.

This Github repository contains the entire code of our project. We have analyzed the Amazon Products dataset to find out the  underlying correlations between its numerical features such as user ratings and prices. 

## HDFS
We have used the HDFS system to store and retrieve our data.

**Dataset Link** : https://drive.google.com/file/d/1RN0F3qSSh2BASsHMm6celc12MqP9A-bk/view?usp=sharing 

## Hadoop and Spark Components Used
### HDFS
Hadoop Distributed File System (HDFS) serves as the backbone for storing massive volumes of data across clusters in big data environments. It ensures fault tolerance by replicating data across multiple nodes, enabling high reliability and accessibility. HDFS facilitates parallel processing by breaking files into blocks distributed across nodes, optimizing data retrieval and processing. Its scalability accommodates petabytes of data, and its write-once-read-many design suits batch processing. HDFS integrates with various big data tools and frameworks, allowing seamless data storage, retrieval, and analytics. Overall, HDFS forms a resilient, scalable, and efficient foundation for managing and processing vast amounts of data in distributed computing architectures.
### Spark Core Engine
The Spark Core Engine is the backbone of PySpark, which provides the essential functionality for task scheduling, memory management, fault recovery and interaction with storage systems. It introduces RDDs (Resilient Distributed Datasets)which allows efficient distributed processing of large-scale data across a cluster of machines. It also includes APIs in various programming languages including Python that helps with real-time data processing, machine learning and more.
### Spark SQL
Spark SQL simplifies big data processing by allowing SQL queries and DataFrame operations on distributed data,as well as offering a familiar interface for data manipulation. It optimizes performance, integrates with diverse data sources and enables the use of user-defined functions. This module streamlines data processing tasks, enhances query optimization, and accommodates structured data handling, making it a versatile and efficient tool for analyzing and processing large-scale datasets in a distributed computing environment.

## Our Cluster
We have used three machines on our cluster where each had 16GB RAM. In total we had 48GB RAM to work with.

## The Use of Vs 
### Volume
Our project includes the Volume aspect of big data since our dataset is huge in size with around 550,000 rows.
### Variety
We have ensured variety in our project since we have used different data formats, structures and sources.
### Value
This project provides value since it shows the underlying patterns between the numerical features, for instance showing the average user rating for a product.
### Visualization
We have demonstrated the quality and interrelations of the data through visualizations such as boxplot.
### Variability
We have demonstrated the level of variability or consistency present in the dataset by showing its outliers through plots.
