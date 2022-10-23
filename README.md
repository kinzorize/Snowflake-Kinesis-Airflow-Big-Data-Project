# Snowflake-Kinesis-Airflow-Big-Data-Project

In this Big Data Project, I build a complete data architecture using snowflake, AWS Services such as Kinesis Data Firehose, Kinesis agent, EC2, S3 and AWS MWAA(Managed Workflow for Apache Airflow) Version 2.2.2

# Data Architecture

An Amazon EC2 logs was created using aws-kinesis-agent.Then the streamed data was sent to kinesis firehose delivery stream which then move it to Amazon S3 Bucket.
Inside the bucket, I created 3 stages namely Landing, processing and processed
