# youtube_analysis
End to end data engineering project using kaggle youtube dataset


Overview
-The goal of this project is to organize, simplify, and analyze structured and semi-structured YouTube video data in a secure manner using video category and trend indicators.



Project Goals:

Data Ingestion — Build a mechanism to ingest data from different sources
ETL System — We are getting data in raw format, transforming this data into the proper format
Data lake — We will be getting data from multiple sources so we need centralized repo to store them
Scalability — As the size of our data increases, we need to make sure our system scales with it
Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
Reporting — Build a dashboard to get answers to the question we asked earlier




Services we will be using:

Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.
