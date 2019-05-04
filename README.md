# serverless-wordpress

## Requirements

1. git
2. docker & docker-compose

Run the following on the Google Cloud Platform.

## STEP 1 : Create Google Cloud Storage Bucket

* Login the GCP Console - https://console.cloud.google.com/cloudshell
* Go To https://console.cloud.google.com/storage/create-bucket

![Create GCS Bucket](https://storage.googleapis.com/datacon2017/step-1-create-gcs-bucket.png)

## STEP 2 : Create WordPress Docker instance

* Go To GCP console - https://console.cloud.google.com/cloudshell
* Clone with git
```
jazzwang_tw@hadoop-tw:~$ git clone https://github.com/jazzwang/serverless-wordpress.gi
t
Cloning into 'serverless-wordpress'...
remote: Counting objects: 10, done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Unpacking objects: 100% (10/10), done.
```
* Check docker-compose version
```
jazzwang_tw@hadoop-tw:~$ docker-compose version
docker-compose version 1.9.0, build 2585387
docker-py version: 1.10.6
CPython version: 2.7.9
OpenSSL version: OpenSSL 1.0.1t  3 May 2016
```
