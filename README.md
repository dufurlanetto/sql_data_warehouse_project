# Data Warehouse and Analytics Project

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## Business Problem
Companies often have large volumes of sales data spread across different sources, making it difficult to consolidate, analyze, and transform this data into reliable information for decision-making. Without a centralized and structured data environment, business teams may struggle to understand customer behavior, product performance and sales trends.


## Solution
This project proposes a modern data warehouse that consolidates sales data from ERP and CRM sources into a centralized analytical environment using a Medallion Architecture. Although this is a portfolio project, the solution was designed around a realistic business scenario and demonstrates how a centralized data environment can support sales, customer and product analysis.

---

## Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:

<img width="1544" height="795" alt="data_architecture" src="https://github.com/user-attachments/assets/ff430051-a6d4-4334-ac85-2890ac57bb19" />

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## BI Analysis
The processed data is consumed by an interactive Power BI dashboard designed to support sales, customer and product analysis.

<img width="1340" height="777" alt="Captura de tela 2026-08-13 170705" src="https://github.com/user-attachments/assets/0ea926b0-5224-42a2-9aac-2e86f4790035" />
<br><br>

> In order to see the full dashboard, please go to the [docs](./docs) folder.
---

## Project Overview
This project involves:

- **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
- **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting**: Developing Power BI reports and dashboards using DAX measures to generate actionable insights.



#### Skills Developed in this Project:
- SQL Development
- Data Architecture
- Data Engineering
- ETL Pipeline Developer
- Data Modeling
- Data Analytics (Power BI & DAX)

---

## Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### BI: Analytics & Reporting (Business Intelligence)

#### Objective
Develop Power BI reports to deliver detailed insights into:

- **Sales performance and trends**
- **Customer behavior**
- **High-performing products and categories**
- **Market and country performance**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.



> [NOTE]
> For more detailed information about the project requirements, please go to the [docs](./docs) folder.

---

## License
This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.
