# 🚀 YouTube Trending Data Engineering Pipeline

An end-to-end **AWS Data Engineering pipeline** that transforms raw YouTube trending data into analytics-ready datasets using **S3, AWS Glue, PySpark and Athena**.

### ⚙️ Pipeline

`S3 → Glue + PySpark → S3 Silver → Glue Catalog → Athena`

### 🛠️ Tech Stack

**Python | PySpark | SQL | AWS S3 | Glue | Athena | Lambda | Step Functions | SNS**

### 🔍 Key Features

* Automated ETL pipeline using **AWS Glue & PySpark**
* Bronze → Silver data lake architecture
* **Data quality validation** using Lambda
* Pipeline orchestration with **Step Functions**
* SQL analytics using **Amazon Athena**
* SNS notifications for pipeline/data-quality events

### 📂 Project Structure

```text
data/             -static data from Kaggle 
glue_jobs/          - PySpark ETL jobs
iam_role_permissions  -IAM permissions
lambda/        - Function for injestion,json_to_parquet,data quality checks
scripts        -aws bash script
step_function  -pipeline orchestration

```

> Built to demonstrate a production-style **cloud ETL and data quality pipeline on AWS**.
