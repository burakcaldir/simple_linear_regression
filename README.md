# Simple Linear Regression
  
### What is Simple Linear Regression?  
  Simple linear regression is a statistical method for obtaining a formula to predict
values of one variable from another where there is a causal relationship between the
two variables
    
### In this post, you will discover exactly how linear regression works step-by-step. After reading this post you will know:
   - How to calculate a simple linear regression step-by-step. 
   ![Running Time Comparison](/image/runningtime.png)  
   - How to perform all of the calculations using a spreadsheet. 
   - How to make predictions on new data using your the model. 
   - A shortcut that greatly simplifies the calculation.
     
### Components of Spark:  
  ![Spark Architecture](/image/sparkarcht.png)  
   - Spark Streaming : Process live streaming data    
   - Spark Sql : Run queries on Hadoop deployment    
   - Mllib : Machine learning libraries built on top of Spark  
   - Graphx : Graph computation engine  
  
### History of Spark APIs:  
   - RDD (2011)  
     - Distribute collection of JVM objects  
     - Functional Operators  
   - DataFrame (2013)
     - Distribute collection of Row objects  
     - Expression-based operations and UDFs  
     - Logical plans and optimizer  
     - Fast/efficient internal representations  
   - DataSet (2015)  
     - Internally rows, externally JVM objects  
     - Type safe + fast
     - But slower than DF. Not as good for interactive analysis  
### Spark & Clusters:  
   Spark supports the following resource/cluster managers:  
   - Spark Standalone – a simple cluster manager included with Spark  
   - Apache Mesos – a general cluster manager that can also run Hadoop applications  
   - Apache Hadoop YARN – the resource manager in Hadoop  
   - Kubernetes – an open source system for automating deployment, scaling, and management of containerized applications  
   - Spark also has a local mode, where the driver and executors run as threads on your computer instead of a cluster, which is useful for developing your applications from a personal computer.  

### Important Terms:  
   - RDD : Resilient Distributed Dataset
   - Transformation : Spark operation that produces an RDD
   - Action : Spark operation that produces a local object
   - Spark Job: Sequence of transformations on data with a final action 
  
### Spark setup for Windows&Anaconda:  
   - Install pyspark using pip install pyspark  
   - Install Java
   - Set environment variables:  
    - PYSPARK_PYTHON = python3  
    - SPARK_HOME = C:\Users\Pc\Anaconda3\Lib\site-packages\pyspark  
   
 ### Pyspark repositories :  
 *[1.NLP using pyspark in Jupyter notebook](/NLP_basics.ipynb)  
 *[1.K-means Clustering using pyspark in Jupyter notebook](/Kmeans_clustering.ipynb) 
 ### Spark & Hadoop :  
 *[1.Brief information about Hadoop ](/Brief_Hadoop.md)
 ### References:  
   - https://machinelearningmastery.com
   - pypi.org  
   - databricks.com
