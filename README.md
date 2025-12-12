** SQL-Data-Warehouse--project**
 
This project showcases a comprehensive data warehousing and analytics solution, spanning the development of a data warehouse to the generation of actionable insights.
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:


**Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.

**Silver Layer:** This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.

**Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.
<img width="800" height="422" alt="image" src="https://github.com/user-attachments/assets/99920614-7cf1-4ddd-89f4-b3a3f5d587d0" />



**Project Overview**

**This project involves:**

**Data Architecture:** Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.

**ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.

**Data Modeling:** Developing fact and dimension tables optimized for analytical queries.

**Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.


**Project Requirements**


**Data Warehouse**

**Objective**

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications**

**Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.

**Data Quality:** Cleanse and resolve data quality issues before analysis.

**Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.

**Scope:** Focus on the latest dataset only; historization of data is not required.

**Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.
