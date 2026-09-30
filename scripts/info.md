# Project Configuration

## S3 Layers

Bronze Layer:
<BRONZE_BUCKET_NAME>

Silver Layer:
<SILVER_BUCKET_NAME>

Gold Layer:
<GOLD_BUCKET_NAME>

Scripts:
<SCRIPTS_BUCKET_NAME>

## AWS Services

Region:
ap-south-1

## Glue Configuration

Bronze Database:
yt-bronze

Bronze Table:
raw_statistics

Silver Database:
yt-silver

Silver Table:
clean_statistics

## Glue Job Arguments

--bronze_database yt-bronze
--bronze_table raw_statistics
--silver_database yt-silver
--silver_bucket <SILVER_BUCKET_NAME>
--silver_table clean_statistics

## Notifications

SNS:
< SNS_TOPIC_ARN >