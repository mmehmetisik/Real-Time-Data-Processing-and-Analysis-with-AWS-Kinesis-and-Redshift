# Real Time Data Processing and Analysis with AWS Kinesis and Redshift
## Project Overview
This project aims to learn real-time data processing and analysis using AWS Kinesis and Redshift services. By utilizing AWS's powerful data processing and analysis tools, we will also explore how to efficiently manage large datasets.

## Technologies Used
1. VPC
2. S3 Bucket
3. IAM
4. Kinesis Data Streams
5. EC2
6. Redshift
7. Kinesis Fire Hose
8. IDE DBeaver

## Architecture
![proje mimarisi](https://github.com/mmehmetisik/Real-Time-Data-Processing-and-Analysis-with-AWS-Kinesis-and-Redshift/assets/64706956/82e40b07-e4cd-4286-a466-4d058680786a)


## Scenario
The project involves processing cryptocurrency data obtained from the Binance API in real-time using AWS EC2, S3, Kinesis Streams, and Kinesis Firehose to transfer the data to AWS Redshift. During this process, data will be continuously streamed through Kinesis Streams, stored in S3, and finally directed to Redshift for analysis and visualization.

## Steps
1. Create a VPC
2. Create an S3 Bucket
3. Create an IAM Role (EC2 => Kinesis)
4. Create a Kinesis Data Stream
5. Launch an EC2 Instance
6. Create a Redshift Subnet Group
7. Reserve an Elastic IP for Redshift
8. Create an IAM Role (Redshift => S3)
9. Launch a Redshift Cluster
10. Configure Inbound Rules for Redshift Cluster
11. Connect to Redshift using DBeaver
12. Create a Kinesis Data Firehose
13. Visualize Data and Create Graphs from Redshift

## License
