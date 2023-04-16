# **YouTube data management in AWS and trend analysis**

## **Overview**
This project aims to extract structured and unstructured YouTube data from Kaggle, manage them in AWS and generate analytical reports based on trending metrics.

## **Project Stages**
1.	Data Ingestion - Build a mechanism to ingest YouTube data
2.	ETL - Extract raw data, transform to compatible format and load
3.	Data Lake – Data is from multiple regions which had to be maintained in centralized repo to store them
4.	Scalability - As the size of data increases, system has to be set to scale up accordingly.
5.	Cloud – AWS is used to manage data
6.	Reporting - Build a dashboard – analytical report

## **Services used**
1.	**Amazon S3**: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2.	**AWS IAM**: Identity and access management manage access to AWS services and resources securely.
3.	**QuickSight**: Amazon Quick Sight is a scalable, serverless, machine learning-powered business intelligence (BI) service built for the cloud.
4.	**AWS Glue**: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5.	**AWS Lambda**: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6.	**AWS Athena**: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

## **Dataset Used**
This Kaggle dataset is a daily record of the top trending YouTube videos. It contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. The field “category_id”, which differs by area, is included in the JSON file linked to the region.
https://www.kaggle.com/datasets/datasnaek/youtube-new

## **Architecture Diagram**

![Untitled Diagram (2)](https://user-images.githubusercontent.com/125311073/232335078-d66b78d8-4f87-4f21-a7af-c73f80d2b31e.jpg)
