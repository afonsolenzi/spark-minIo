# spark + minIo

## reading a csv and saving as parquet on bronze as a test scenario.
### to execute same scenario in your machine, please:
#### - have functional spark/pyspark
#### - download and install minIo. Also add the mentioned jars you can find in the spark session creation.
#### - clone this repo
#### - adapt to your scenario
#### - run entire notebook.


### Why Minio?
MinIO offers high-performance, S3 compatible object storage. Native to
Kubernetes, MinIO is the only object storage suite available on every public
cloud, every Kubernetes distribution, the private cloud and the edge. MinIO
is software-defined and is 100% open source under GNU AGPL v3.
https://min.io/

### Why Spark?
#### https://spark.apache.org/


### This is the high level architecture
![Screenshot](Spark+Minio.png)


### This is the output on bronze for tests
![Screenshot](output-bronze.png)


