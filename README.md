<div align="center">

# Daniel Abraham R

### Data Engineer | AWS | Apache Spark | PySpark | Airflow | dbt | Lakehouse

**Building scalable data platforms, distributed data pipelines, and cloud-native data solutions.**

[![GitHub](https://img.shields.io/badge/GitHub-DannyBoy3310-181717?style=flat&logo=github)](https://github.com/DannyBoy3310)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0A66C2?style=flat&logo=google-chrome&logoColor=white)](https://daniel-portfolio-lemon.vercel.app)

</div>

---

## 👨‍💻 About Me

I'm a **Data Engineer with 4+ years of experience** designing, building, and optimizing scalable data platforms and distributed data processing solutions.

Currently working as a **Data Engineer Consultant at Deloitte USI**, with previous experience at **Tata Consultancy Services (TCS)**.

My work focuses on building reliable and scalable data systems using **AWS, Apache Spark, PySpark, Python, SQL, Apache Airflow, dbt, and modern lakehouse technologies**.

I enjoy solving problems around **large-scale data processing, ETL/ELT, workflow orchestration, data platform modernization, performance optimization, and cloud cost efficiency**.

- 💼 **Current Role:** Data Engineer Consultant — Deloitte USI
- 🧑‍💻 **Experience:** 4+ years in Data Engineering
- ☁️ **Cloud:** AWS
- ⚡ **Processing:** Apache Spark / PySpark
- 🔄 **Orchestration:** Apache Airflow / AWS MWAA
- 🧱 **Architecture:** Data Lake, Lakehouse, Medallion Architecture
- 🧩 **Transformation:** dbt, SQL, PySpark
- 🗂️ **Storage:** Amazon S3, Apache Iceberg
- 📊 **Analytics:** Amazon Redshift
- 📈 **Scale:** 1TB+ data processing experience
- 🐳 **Containers:** Docker
- 🔧 **Development:** Python, SQL, Bash

---

# 🛠️ Tech Stack

### 👨‍💻 Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat&logo=gnubash&logoColor=white)

### ⚡ Data Engineering

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-4B5563?style=flat)

`PySpark` · `ETL` · `ELT` · `Data Modeling` · `Data Quality` · `Distributed Processing`

### ☁️ AWS

![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat&logo=amazons3&logoColor=white)
![AWS Glue](https://img.shields.io/badge/AWS%20Glue-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Amazon EMR](https://img.shields.io/badge/Amazon%20EMR-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Amazon%20Redshift-8C4FFF?style=flat&logo=amazonredshift&logoColor=white)
![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Amazon Kinesis](https://img.shields.io/badge/Amazon%20Kinesis-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Amazon CloudWatch](https://img.shields.io/badge/Amazon%20CloudWatch-FF4F8B?style=flat&logo=amazonaws&logoColor=white)

`S3` · `Glue` · `EMR` · `Redshift` · `EC2` · `MWAA` · `Kinesis` · `SNS` · `CloudWatch`

### 🗄️ Databases & Storage

`Amazon Redshift` · `Oracle` · `DB2` · `MySQL` · `MongoDB` · `Amazon S3` · `MinIO`

### 🔧 Engineering & Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

`Boto3` · `Pandas` · `NumPy` · `Jinja2` · `CI/CD` · `REST APIs`

---

# 🏗️ Featured Projects

## 🔹 Metadata-Driven Data Ingestion Framework

**PySpark · SQL · Apache Airflow · AWS Glue · Amazon S3**

A reusable metadata-driven ingestion framework designed to standardize data ingestion and reduce repetitive pipeline development.

### Key Features

- Metadata-driven pipeline execution
- Reusable PySpark ingestion components
- Parameterized ingestion workflows
- Apache Airflow orchestration
- AWS Glue Data Catalog integration
- Configurable source-to-target processing
- Scalable batch data processing

### Architecture

```text
                Data Sources
                     │
                     ▼
              ┌─────────────┐
              │  Metadata   │
              │ Configuration│
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │   Airflow   │
              │     DAG     │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │   PySpark   │
              │   Engine    │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │   Amazon S3 │
              │  Data Lake  │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │ Glue Catalog│
              └─────────────┘
