# serverless-wordpress

## Requirement

1. git
2. docker & docker-compose

為了方便展示整個流程，以下直接採用 Google Cloud Platform 來進行展示。

## STEP 1 : 建立 Google Cloud Storage 的 Bucket 供後續儲存靜態網站使用

* 登入 GCP 的 Console
* 連線至 https://console.cloud.google.com/storage/create-bucket

![建立 GCS Bucket](https://storage.googleapis.com/datacon2017/step-1-create-gcs-bucket.png)

## STEP 2 : 開啟 WordPress Docker instance

* 開啟 GCP console - https://console.cloud.google.com/cloudshell
* 使用 git 複製程式碼
```
jazzwang_tw@hadoop-tw:~$ git clone https://github.com/jazzwang/serverless-wordpress.gi
t
Cloning into 'serverless-wordpress'...
remote: Counting objects: 10, done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Unpacking objects: 100% (10/10), done.
```
* 檢查 docker-compose 版本
```
jazzwang_tw@hadoop-tw:~$ docker-compose version
docker-compose version 1.9.0, build 2585387
docker-py version: 1.10.6
CPython version: 2.7.9
OpenSSL version: OpenSSL 1.0.1t  3 May 2016
```
