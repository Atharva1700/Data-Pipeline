# Data Pipeline Project

This project demonstrates a complete data pipeline for real-time and batch data processing using modern data engineering tools. It is designed to simulate a real-world workflow involving data ingestion, processing, and storage using Apache Kafka, Apache Airflow, AWS Glue, and S3-compatible storage (MinIO).

## 🧰 Tech Stack

- **Python 3.9**
- **Apache Kafka** (KRaft mode)
- **Apache Airflow**
- **Docker & Docker Compose**
- **MinIO** (as an S3 bucket alternative)
- **AWS Glue**
- **PySpark**
- **Kafka Producer/Consumer**
- **Jupyter Notebook** (for analysis and testing)

## 🔁 Pipeline Overview

1. **Data Ingestion**: Simulated data is streamed via a Kafka Producer.
2. **Real-time Streaming**: Kafka Consumer processes incoming messages.
3. **Storage**: Processed data is stored in a MinIO bucket.
4. **Orchestration**: Apache Airflow automates and schedules ETL tasks.
5. **Transformation**: AWS Glue scripts handle data cleaning and transformation.
6. **Final Output**: Cleaned data is stored in MinIO and can be analyzed via Jupyter Notebook.

## 📂 Project Structure

