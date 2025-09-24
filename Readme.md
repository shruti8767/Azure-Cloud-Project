**Azure Cloud Data Engineering Project**

**Project Overview**

- This project demonstrates an end-to-end data engineering solution on Microsoft Azure Cloud. It covers the complete lifecycle of data ingestion, transformation, storage, and analytics using Azure Data Factory, Azure Storage, Azure Synapse Analytics, and PySpark.

- The dataset used is a Brazilian E-commerce dataset from Kaggle, which provides detailed transactional, customer, and geographic data.

**Key Objectives**

1. Build a robust ETL/ELT pipeline to ingest and transform large datasets.

2. Leverage Azure Data Factory to orchestrate data pipelines.

3. Store raw and processed data efficiently using Azure Storage Accounts.

4. Use Azure Synapse Analytics for scalable data warehousing and analytics.

5. Implement data transformations with PySpark for processing and cleansing.

**Architecture**

**Data Ingestion:**

- Data is ingested from the Kaggle e-commerce dataset into Azure Blob Storage.

**Data Transformation:**

- PySpark scripts transform and clean the raw data.

- Data quality checks and validations are performed during processing.

**Data Orchestration:**

- Azure Data Factory pipelines orchestrate the workflow from ingestion to transformation to storage.

**Data Storage and Analytics:**

- Transformed data is stored in Azure Synapse for analytics.

- Enables reporting and insights generation on customer behavior and sales trends.

**Technologies Used**

1. Azure Data Factory (ADF) – Pipeline orchestration and workflow automation

2. Azure Storage Account – Raw and processed data storage

3. Azure Synapse Analytics – Data warehouse for analytics

4. PySpark – Data processing and transformations

5. Kaggle Brazilian E-commerce Dataset – Sample dataset for demonstration

**Project Highlights**

- Designed and implemented end-to-end ETL pipeline in Azure.

- Processed and transformed large-scale e-commerce data using PySpark.

- Applied data quality checks to ensure clean and reliable datasets.

- Enabled scalable analytics using Azure Synapse for business insights.

**How to Run**

Clone the repository:

git clone https://github.com/shruti8767/Azure-Cloud-Project


Open the project in Azure Synapse Studio or Azure Databricks.

Configure Azure Storage Account credentials.

Trigger Azure Data Factory pipelines to ingest and process the data.

View processed data and analytics in Azure Synapse Analytics.

**Dataset**

Brazilian E-commerce dataset from Kaggle: https://www.kaggle.com/datasets

Includes customer orders, payments, products, and geolocation information.

**Outcome**

Successfully built a cloud-based data pipeline for e-commerce analytics.

Gained hands-on experience with Azure Data Factory, Storage, Synapse, and PySpark.

Generated insights that could support business decision-making in real-world e-commerce scenarios.
