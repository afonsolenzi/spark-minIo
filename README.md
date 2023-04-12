# spark + minIo
### This is the high level architecture. Instructions bellow:
![Screenshot](Spark+Minio.png)

## Reading a csv and saving as parquet on bronze for a test scenario.
### to execute same scenario in your machine, please:
#### - have functional spark/pyspark. I am using 3.3.2 and Java 8.
#### - I tested it on Vscode and Pycharm for a reference
#### - download and install minIo. Also add the mentioned jars you can find in the spark session creation.
#### - Login into your minIo using: 
#####".\minio.exe server C:\minio --console-address :9090"
#### - clone this repo to your machine
#### - adapt to your scenario, csv path, passwords, buckets
#### - run entire notebook.


### Why Minio?
MinIO offers high-performance, S3 compatible object storage. Native to
Kubernetes, MinIO is the only object storage suite available on every public
cloud, every Kubernetes distribution, the private cloud and the edge. MinIO
is software-defined and is 100% open source under GNU AGPL v3.
https://min.io/

### Why Spark?
#### https://spark.apache.org/





### This is the output on bronze for tests
![Screenshot](output-bronze.png)


