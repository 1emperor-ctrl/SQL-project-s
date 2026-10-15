# 💡 Modern Data Warehouse & Analytics Solution

Welcome to the **Data Warehouse and Analytics Project**! 🚀

This repository provides an end-to-end implementation of an analytical data warehouse built with **SQL Server**. Designed as a practical portfolio project, it illustrates industry best practices across the full data lifecycle.

------
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

------
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.
------
## 🚀 Project Requirements
 
### Constructing the Data Warehouse (Data Engineering) 
#### Objective
Create an end-to-end SQL Server data warehouse to centralize sales data for analytical reporting and informed decision-making.

### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Resolve data errors and refine quality before analyzing the dataset.
- **Integration**: Merge both data sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.


---
### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights deliver key business metrics to stakeholders, driving strategic and informed decision-making.

---
## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---
## 🌟 About Me

Hi there! I'm **Siddhanth Muddiah**, also known as **SID**. I’m an IT professional and passionate YouTuber on a mission to share knowledge and make working with data enjoyable and engaging!
