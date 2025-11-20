# Real-Time-User-Clickstream-Analytics
This repository demonstrates how to build a comprehensive real-time analytics solution using AWS services to capture, process, and analyze user clickstream data. The solution enables organizations to gain valuable insights into user behavior and make data-driven decisions to enhance user engagement and drive business growth.


It showcases modern data architecture patterns that allow organizations to:

* Capture and analyze user interactions in real-time
* Understand user behavior patterns
* Create personalized user experiences
* Make informed, data-driven decisions
* Support business growth through actionable insights

* Learning Outcomes
You will learn how to build a modern data lake architecture using AWS S3 Tables. This workshop will guide you through the process of ingesting streaming data, configuring storage optimization, and implementing data governance - all while leveraging AWS's latest data lake technologies. This workshop demonstrates how to create an end-to-end data lake solution using various AWS services including Amazon Kinesis, Data Firehose, S3 Tables, AWS Lake Formation, Amazon Athena, and Amazon Quick Suite. You'll learn how to handle streaming data ingestion, optimize storage patterns, manage data governance, and create analytical visualizations.

Key AWS Services Covered
Data Producer: for this workshop we will use a Kinesis Data Generator that simulates streaming data. Some examples of real time data producers include IoT sensors, clickstream web applications, smart devices, and gaming applications.
Amazon Kinesis Data Stream  is a real time data streaming service that captures and processes large amounts of data. It enables users to ingest real-time data from various sources.
Amazon Data Firehose captures near real-time data and delivers the processed data stream to various destinations. For this lab, we will be pointing it to our S3 table. We will also leverage AWS Lambda to transform the records in near real-time AWS Lambda  is a serverless compute service that runs your code in response to events and automatically manages the underlying compute resources for you.
S3 Tables  are feature of S3 which offer purpose-built storage for tabular data (columns and rows), such as daily purchase transactions, streaming sensor data, or ad impressions. S3 table have built in Apache Iceberg support.
Lake Formation  is a managed service that makes it easy to set up, secure, and manage your data lakes. It control access to your S3 data catalogs and for that reason, you will have to grant the needed permissions to write to your S3 tables.
Amazon Athena  is a query service that enables running SQL queries directly on data stored in S3. In this lab you will use Athena to run DDL statements on the data you have stored in your S3 table.
Amazon Quick Suite  is AWS's new agentic teammate that quickly answers your questions at work and turns those insights into actions for you. Instead of switching between multiple applications to gather data, find important signals and trends, and complete manual tasks, Quick Suite brings AI-powered research, business intelligence, and automation capabilities into a single workspace. You can now analyze data through natural language queries, find critical information across enterprise and external sources in minutes, and automate processes from simple tasks to complex multi-department workflows.

