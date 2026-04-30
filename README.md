# project_transportation
Built an end-to-end data engineering pipeline using Databricks with a declarative approach. The project ingests raw data from Amazon S3, processes it through Bronze, Silver, and Gold layers, and produces structured datasets for analysis using Delta Live Tables.
# Declarative Data Engineering Pipeline using Databricks & AWS S3

## Overview
This project demonstrates an end-to-end data engineering pipeline built using Databricks. The pipeline ingests raw data from Amazon S3, processes it using a declarative approach, and transforms it into structured datasets for analysis.

The goal of this project was to understand how modern data pipelines are built using cloud storage and automated data workflows.

---

## Project Architecture

The pipeline follows a layered approach:

S3 (Raw Data) → Databricks Pipelines → Bronze → Silver → Gold

- **Bronze Layer**: Raw data ingestion from S3  
- **Silver Layer**: Data cleaning and transformation  
- **Gold Layer**: Final datasets ready for analysis  

(Add architecture.png image here)

---

## Key Features

- Data ingestion from Amazon S3  
- Built using Databricks declarative pipelines (Delta Live Tables)  
- Structured using Medallion Architecture  
- Automated data transformations  
- Supports scalable and reusable pipeline design  

---

## Technologies Used

- Databricks  
- PySpark  
- Delta Live Tables (DLT)  
- Amazon S3  
- SQL  

---

## What I Learned

- How to design a real-world data pipeline using a declarative approach  
- Working with cloud-based storage (S3)  
- Managing data flow across multiple layers (Bronze, Silver, Gold)  
- Understanding how automated pipelines simplify ETL processes  

---

## Project Structure
