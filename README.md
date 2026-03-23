# Transaction Data Processing using Azure Databricks

## Overview

This project demonstrates an end-to-end data pipeline built using Azure Databricks and Delta Lake to process customer transaction and loan datasets. The pipeline follows a layered architecture (Bronze, Silver, Gold) to ensure scalable and structured data processing.

---

## Architecture

The data pipeline is designed using a multi-layer architecture:

* **Bronze Layer**: Raw data ingestion from CSV files into ADLS Gen2
* **Silver Layer**: Data cleaning, transformation, and deduplication using PySpark
* **Gold Layer**: Aggregated and curated data stored in Delta tables for reporting

---

## Tools & Technologies

* Azure Databricks
* PySpark
* Delta Lake
* Azure Data Lake Storage Gen2 (ADLS)
* Azure Data Factory (ADF)
* Power BI

---

## Data Flow

1. Raw data (accounts, customers, transactions, loans) is ingested into ADLS (Bronze layer)
2. Databricks notebooks process and clean the data
3. Transformations are applied using PySpark (filtering, joins, aggregations)
4. Processed data is stored in Silver and Gold layers using Delta Lake
5. Data is used for reporting and visualization in Power BI

---

## Key Features

* Implemented Bronze, Silver, Gold architecture
* Used PySpark for data transformation and processing
* Implemented incremental data loading
* Optimized Delta tables for better performance
* Orchestrated workflows using Azure Data Factory
* Integrated processed data with Power BI dashboards

---

## Project Structure

/databricks-notebooks/
/adls-data/
/delta-tables/
/architecture-diagram/

---

## Screenshots

(Add screenshots here)

* Databricks Notebook Execution
* Delta Table Output
* Data Transformation Steps
* Pipeline Orchestration (ADF Trigger)

---

## Learnings

* Hands-on experience with PySpark and Delta Lake
* Understanding of data pipeline architecture and workflow orchestration
* Experience in building scalable and efficient data processing solutions

---

## Conclusion

This project demonstrates the ability to build and manage scalable data pipelines using Azure Databricks and Delta Lake, following industry-standard data engineering practices.
