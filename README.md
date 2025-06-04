# ecommerce-bigdata-spark
# E-Commerce Big Data Analysis with PySpark

This repository contains the analysis of a large e-commerce dataset (October 2019) using Apache Spark and Hive on Google Cloud Platform (GCP). The analysis is designed to run on Dataproc clusters with Spark and Hive enabled.

## Files

- `analysis.py`: The main PySpark script that performs data loading, cleaning, and SQL-based analysis

## Requirements

- Apache Spark 3.x
- Python 3.8+
- Google Cloud Storage (GCS)
- Hive (optional for SQL querying)

## Running on GCP Dataproc

1. Upload the CSV file to a GCS bucket (e.g., `gs://your-bucket-name`)
2. Create a Dataproc cluster with Spark & Hive optional components
3. SSH into the master node
4. Start PySpark with:
   ```bash
   pyspark --master yarn
