# spark-rapids-dataproc-lab

## 1. Overview Customer Churn
This demo is derived from [data-science-blueprints](https://github.com/NVIDIA/data-science-blueprints) repository.
The repository shows a realistic ETL workflow based on synthetic normalized data. 

## 2. Services Used
* Google Cloud Storage
* Google Cloud Dataproc

## 3. Permissions / IAM Roles required to run the lab

Following permissions / roles are required to execute the serverless batch

- Viewer
- Dataproc Editor
- Service Account User
- Storage Admin

<br>

## 4. Checklist

To perform the lab, below are the list of activities to perform. <br>

[1. GCP Prerequisites]()<br>
[2. Spark Rapids GPU Server Setup with Init Scripts]()<br>
[3. Generate Synthetic Dataset and update to GCS]()<br>

## 5. Lab Modules

The lab consists of the following modules.

1, Create Dataproc cluster and set up runtime environment
2, Use CPU Spark to process the data and generate Spark history Log
3, Use Spark RAPIDS Qualification Tool to exam the history log 
4, Use Spark RAPIDS to process the data
5, Use Spark RAPIDS Profiling Tool to compare CPU/GPU history log to understand performance

There are 2 ways of perforing the lab.
- Using [Google Cloud Shell]()
- Using [GCP console]()

<br>


## 6. CleanUp

Delete the resources after finishing the lab. <br>
Refer - [Cleanup]()

<br>
