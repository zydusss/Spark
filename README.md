## What is Spark

Spark is a fast , scalable, general purpose engine for large scale data processing. 
* Written in Scala : Functional programming language that runs on top of JVM.

Spark comes in multiple flavours :
* Spark Shell(Python or Scala) : Interactive data processing / exploration
* Spark Applications : For large scale data processing needs. 

#### Spark Context
- Main entry point to the Spark API.
- Spark shell provides a preconfigured Spark context called 'sc'

#### Spark RDD (Resilient Distributed Dataset)
RDD are fundamental unit of data in Spark. Most of the processing in Spark is done on RDDs.
RDD are immutable which allows : Consistency,Concurrency,Easy & deterministic recreation. 

- Resilient : If data in memory is lost, it can be recreated.
- Distributed : Processed accross the cluster
- Dataset : holds data which may come from hetrogenous sources (like file,database etc.) or created programmatically. 

#### Spark MLlib
 * What is Spark MLlib ?
 
 * Why you should be using Spark MLlib ?
 
 * How ?
 
#### Spark Streaming
 * What is Spark Streaming ?
 
   * An extension of core Spark.
   
   * Provides capability for real time processing of streaming data.
   
   * Use cases : Continous ETL , Website Monitoring , Fraud detection , Ad monetization , Social media analysis , Financial market trends
 
 * Why you should be using Spark Streaming ?
 
   * Integrates batch and real-time processing
   
   * Easy to develop : uses Spark's high level API
   
   * "Once and only once" processing
   
   * Second-scale latencies
   
   * Scalability and efficient fault tolerance 
 
  * How ? 
 
   * Divide data stream into batches of n seconds
     * Called a Dstream (Discretized Stream)
     
   * Process each batch in Spark as an RDD
   
   * Return results of RDD operations in batches
   
#### Spark GraphX
 * What is Spark GraphX ?
 
 * Why you should be using Spark GraphX ?
 
 * How ?

##### For further details along with code snippets(pyspark) follow the topics listed below :

* [Setting up Spark on Ubuntu - Jupyter Notebook](https://github.com/zydusss/Spark/blob/master/Launching%20Spark%20On%20Ubuntu.ipynb)
* [Creating Spark RDD's](https://github.com/zydusss/Spark/blob/master/Creating%20Spark%20RDD.ipynb)
* [Creating Spark Dataframes](https://github.com/zydusss/Spark/blob/master/Creating%20Spark%20Dataframe.ipynb)
* [Spark Transformations & Actions](https://github.com/zydusss/Spark/blob/master/Spark%20Transformations%20%26%20Actions.ipynb) 
  
