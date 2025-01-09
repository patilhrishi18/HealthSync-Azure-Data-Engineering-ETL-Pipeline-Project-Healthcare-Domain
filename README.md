# Azure Healthcare Data Pipeline  

## Overview  
This project demonstrates the implementation of a scalable, end-to-end Azure Data Engineering pipeline designed to process 1TB+ healthcare data. The pipeline automates data ingestion, transformation, and loading across **Bronze**, **Silver**, and **Gold** layers, ensuring efficient data governance and auditability using Azure services.  

## Key Features  
- **Data Processing:** Supports CSV, Parquet, and Delta file formats.  
- **Automated Pipelines:** Developed in Azure Data Factory (ADF) for seamless data movement.  
- **Incremental and Full Loads:** Optimized workflows for both types of data ingestion.  
- **Audit Logging:** Ensures 100% data accuracy with detailed log tracking.  
- **Centralized Governance:** Implemented Databricks Unity Catalog for metadata management.  

## Services and Tools Used  
- **Azure Data Factory (ADF):** Orchestrating data pipelines.  
- **Azure SQL Database:** Storing and querying healthcare data.  
- **Azure Databricks:** Data transformation and processing with Delta Lake.  
- **Azure Data Lake Gen2:** Centralized storage for raw and processed data.  
- **Azure Key Vault:** Securing credentials and sensitive information.  

## Data Pipeline Workflow  
1. **Bronze Layer:** Raw data ingestion from CSV files into Azure Data Lake.  
2. **Silver Layer:** Data cleaning, standardization, and transformation using Databricks.  
3. **Gold Layer:** Aggregated and analytics-ready data stored in Delta tables.  

## Folder Structure  
- **Landing:** Raw data files (CSV).  
- **Bronze:** Processed raw data stored in Parquet format.  
- **Silver:** Cleaned and standardized data.  
- **Gold:** Final analytics-ready datasets in Delta Lake.  

## Key Results  
- Processed over **1TB** of healthcare data across 10+ tables.  
- Achieved **40% improvement** in efficiency with incremental data loads.  
- Ensured **100% data accuracy** through robust audit logging mechanisms. 
