# Databricks-Project
This repository contains end to end data bricks project.

# Retail Sales Intelligence Platform – Databricks

## 📌 Overview
This project demonstrates a complete **end-to-end Databricks Lakehouse architecture**
using **PySpark, Delta Lake, SQL, MLflow, and Streaming**.

It follows enterprise best practices such as:
- Medallion Architecture (Bronze → Silver → Gold)
- Incremental CDC-style processing
- Structured Streaming
- Data Quality Validation
- SQL Analytics & Dashboards
- Machine Learning with MLflow
- Workflow Orchestration
- AI-powered analytics (Databricks Genie)

---

## 🧱 Architecture
Raw Data → Bronze → Silver → Gold → Analytics / ML

---

## 📂 Dataset
Databricks public retail dataset:
`/databricks-datasets/retail-data/by-day/`

---

## 🔧 Technologies Used
- Databricks Free Edition
- PySpark
- Spark SQL
- Delta Lake
- Structured Streaming
- MLflow
- Databricks Workflows
- Databricks SQL & Dashboards

---

## 📘 Notebooks
| Notebook | Description |
|--------|------------|
| 01_bronze_ingestion | Raw data ingestion |
| 02_silver_transformations | Cleaning & CDC merge |
| 03_gold_aggregations | Business metrics |
| 04_data_quality_checks | Data validation |
| 05_streaming_pipeline | File-based streaming |
| 06_ml_training_mlflow | ML model training |
| 07_model_inference | Predictions & evaluation |

---

## 📊 Analytics
SQL dashboards provide insights into:
- Revenue by country
- Transaction volume
- Average order value

---

## 🤖 Machine Learning
- Revenue prediction model
- MLflow experiment tracking
- Model evaluation with RMSE

---

## 🚀 Key Learnings
- Built a full Lakehouse architecture
- Implemented batch + streaming pipelines
- Applied CDC-style incremental loads
- Trained and evaluated ML models
- Designed analytics-ready datasets

---

## 📌 Resume Highlight
> Built an end-to-end Databricks Lakehouse with Spark, Delta Lake, streaming ingestion,
CDC processing, MLflow-based ML pipelines, and SQL dashboards.

