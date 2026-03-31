# Flipkart Product Data Analysis | PySpark & Databricks

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![SparkSQL](https://img.shields.io/badge/Spark_SQL-FFA500?style=for-the-badge&logo=apachespark&logoColor=white)
![ETL](https://img.shields.io/badge/ETL_Pipeline-4CAF50?style=for-the-badge)

## Overview
An end-to-end ETL data pipeline built using Python and PySpark on Databricks
to process and analyse 5,200+ Flipkart e-commerce records across 14 columns
including product ratings, pricing, reviews, and categories.

# Flipkart Product Data Analysis | PySpark & Databricks

## Overview
An end-to-end ETL data pipeline built using Python and PySpark on Databricks
to process and analyse 5,200+ Flipkart e-commerce records across 14 columns
including product ratings, pricing, reviews, and categories.

## Steps Involved

### 1. Data Ingestion
- Loaded raw CSV data into PySpark DataFrame using SparkSession
- Inspected schema and statistical summary across 14 columns

### 2. Data Cleaning
- Detected missing values across 3+ columns using isNull()
- Applied dropna() and fillna() to ensure 100% data consistency

### 3. Data Transformation
- Filtered high-rated products (Rating > 4)
- Calculated average ratings grouped by 3 product categories
- Aggregated revenue metrics using groupBy() and agg()

### 4. Data Storage
- Saved cleaned and transformed output as a structured table
- Validated final output using Spark SQL queries

## Key Insights
- Identified top-rated products across Men, Women categories
- Analysed pricing distribution across 5,200+ records
- Ensured analytics-ready data output for business consumption

## Dataset
Flipkart product dataset — 5,200+ records, 14 columns

## Live Notebook
- Python
- PySpark
- Databricks
- Spark SQL


## Dataset
Flipkart product dataset — 5,200+ records, 14 columns

## Live Notebook
[View on Databricks](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/19652298897236/3492530066299206/4655662666255799/latest.html)
