# ETLProject
A bank is trying to observe the withdrawal behavior and the corresponding dependent factors to optimally manage the refill frequency of its ATMs.
To achieve the above objection, the following tasks are performed.

1. Extracting the transactional data from a given MySQL RDS server to HDFS(EC2) instance using Sqoop. 
2. Transforming the transactional data according to the given target schema using PySpark.   
3. This transformed data is to be loaded to an S3 bucket. 
4. Creating the Redshift tables according to the given schema. 
5. Loading the data from Amazon S3 to Redshift tables. 
6. Performing analysis using RedShift queries.
