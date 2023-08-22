# kafka-stock-market-project

Stock Market Kafka Real-Time Data Engineering Project

# Introduction

In this project, you will execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.
We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

# Architecture

   ![ACTION PLAN](https://github.com/iparth36i/kafka-stock-market-project/assets/74725717/e8f0f52c-bc98-40b0-809e-7c1af64fec81)


# Technology Used

=> Programming Language - Python
=> Amazon Web Service (AWS)
=> S3 (Simple Storage Service)
=> Athena
=> Glue Crawler
=> Glue Catalog
=> EC2
=> Apache Kafka

# Dataset Used

/data folder - indexProcessed.csv
You can use any dataset, we are mainly interested in the operation side of Data Engineering (building data pipelines)

# PROCESS

1) Create an AWS account
   
2) Launch Instance
   
3) Start a session to connect your ec2 instance
   
4) Download Kafka
   
5) Download Java as Kafka works on Java
    
6) Run Zookeeper
    
7) Run the Kafka server

      ![zookeeper-server_started](https://github.com/iparth36i/kafka-stock-market-project/assets/74725717/65e0e547-5b86-4ea5-aac2-387d8278fe34)

8) Create a new topic

      ![topic-created](https://github.com/iparth36i/kafka-stock-market-project/assets/74725717/14e46da0-3a8f-4378-bdf2-75548cc277e9)
   
9) Start your producer

      ![producer started](https://github.com/iparth36i/kafka-stock-market-project/assets/74725717/81f0ffb3-ae6d-439d-b2fb-272d0cfd937d)
    
10) Start your consumer

       ![data_consumed](https://github.com/iparth36i/kafka-stock-market-project/assets/74725717/e90c9d73-790a-4a21-abd5-104a23214482)

11)  Connection established
    
12)  Now write your data on the S3 bucket by authenticating AWS CLI

        ![data_stored_s3_bucket](https://github.com/iparth36i/kafka-stock-market-project/assets/74725717/70ef1831-f52e-4b09-a10a-59572de9cd92)

13)  Create a catalog table using the AWS Glue crawler
    
14)  Use AWS Athena to write queries on REAL-TIME DATA

        ![aws_athena_SQL_implimentation](https://github.com/iparth36i/kafka-stock-market-project/assets/74725717/c740ca55-453e-4b18-bf65-cc0ca3285b47)


