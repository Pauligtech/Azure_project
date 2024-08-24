# End-to-End Data Engineering Project: Azure, Databricks, and Power BI 

### This project demonstrates an end-to-end data engineering workflow using Azure services, Databricks, and Power BI for efficient data transfer, processing, and reporting.

## Project Overview
### The objective of this project is to migrate sales data from an on-premise SQL Server to cloud storage, process and transform the data in Databricks, and visualize the results using Power BI for daily reporting

## Sections
### 1. Azure Project
#### SQL Server Migration: Data is first transfered from an on-premise SQL Server to Azure cloud storage. The migration process ensures data is securely stored and accessible for further processing.
#### Data Pipelines: A data pipeline is created using Azure Data Factory to automate the daily transfer of sales data to Azure Data Lake Storage Gen2. This pipeline is designed to handle large volumes of data efficiently, ensuring daily updates are seamless and error-free.
### 2. Databricks Integration
#### Data Processing with PySpark: Once the data is in Azure Storage, PySpark is used within Databricks to move and process the data. This step involves transforming raw data into a structured format, suitable for analytics.
#### Creating Delta table: Using Spark SQL, a delta table is created in the Databricks environment. This table store aggregated sales data, which optimizes performance for subsequent queries and analytics tasks.
### 3. Power BI Reporting
#### Dashboard Development: The final step involves developing a Power BI dashboard that connects to the delta table in Databricks. This dashboard provides a comprehensive view of the daily sales data, enabling stakeholders to make informed business decisions based on real-time insights.

## Getting Started
### To implement this project, you will need access to the following:

#### - Azure Subscription (for Data Factory, Data Lake Storage Gen2, and Databricks)
#### - Power BI Desktop (for dashboard development)
#### - SQL Server (for the on-premise database)

## Instructions
### - Set up Azure Services: Begin by configuring Azure Data Factory and Data Lake Storage Gen2. Ensure the on-premise SQL Server is connected for data migration.
### - Configure Databricks: Set up a Databricks environment and use PySpark to process and move the data to Delta Tables.
### - Build Power BI Dashboard: Connect Power BI to the Delta Tables and design the dashboard to visualize daily sales metrics.

## Conclusion
### This project serves as a robust framework for implementing an end-to-end data engineering solution, leveraging the power of Azure, Databricks, and Power BI. It ensures data is efficiently migrated, processed, and visualized, providing valuable insights for business decision-making.
