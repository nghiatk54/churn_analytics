# churn_analytics
Data pipline end to end: Customer Churn Data Analytics
Data (load) -> S3 Bucket -> AWS Glue Crawlers -> AWS Glue Data Catalog:
    1. -> Amazon Athena (query) <--> User
    2. -> Amazon Redshift -> PowerBI