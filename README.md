# 📦 ETL-Driven Data Warehouse Design and BI Reporting for Retail Analytics

This project was developed as part of the MSc in Data Analytics (Semester 2) curriculum. It demonstrates the end-to-end development of a data warehousing and reporting solution using SSIS and Tableau, with a strong emphasis on ETL pipelines and retail business insights.

## 📌 Overview

The goal of the project was to design a data warehouse for retail sales analysis using a star schema and build automated ETL processes for loading data. This data was later used to generate insightful business intelligence dashboards using Tableau, including customer segmentation, product performance, and regional sales.

## 🎯 Objectives

- Develop a **star schema data warehouse** using SQL Server.
- Build **ETL pipelines** using SSIS to extract, transform, and load structured data.
- Create **Tableau dashboards** to visualize customer behavior, sales trends, and product analytics.
- Focus data on the **Australian retail market**, applying filters and transformations.

## 🛠️ Tech Stack

- **SQL Server** – Data warehouse backend
- **SSIS (SQL Server Integration Services)** – ETL development
- **Tableau** – Interactive visual analytics
- **Microsoft Excel** – Source data
- **Visual Studio** – SSIS development environment

## 🗃️ Data Model

- **Fact Table**: `FactSalesOrder` (sales, profits, etc.)
- **Dimension Tables**:
  - `DimCustomer` – Customer data (segment, city, etc.)
  - `DimProduct` – Product metadata (category, price, etc.)
  - `DimDate` – Date hierarchy (year, month, etc.)
  - `DimLocation` – Australian states, cities
  - `DimDepartment` – Internal department references

## 🔄 ETL Process (SSIS)

- Extracted data from Excel sources with over 65,000 rows
- Applied **conditional splits** to filter only Australian records
- Loaded cleaned, transformed data into corresponding dimension and fact tables
- Used **Lookups and Derived Columns** for schema alignment and enrichment

## 📊 Reports & Dashboards

Developed interactive dashboards using Tableau:
- **Regional Sales** – Compare sales across Australian states
- **Product Performance** – Identify top and underperforming products
- **Monthly Sales Trends (2015–2018)** – Detect seasonality
- **Customer Segmentation** – Group customers by profile and behavior

## 📸 Visualizations

### Tableau Dashboards

![Dashboard](https://github.com/user-attachments/assets/8205272f-9b2b-442d-a240-6219405f3b49)

## 📁 Project Structure

```
📦 DataWarehouse_ETL_Project
├── SQL_Scripts/              # Schema and table creation scripts
├── SSIS_ETL/                 # .dtsx packages for each table
├── Tableau_Dashboards/       # Packaged workbooks (.twbx) or Tableau visuals
├── Visualizations/           # Screenshot images
└── Documentation/
    └── CA_Datastorage_Group_Report.pdf
```

## 👨‍💻 Authors

- Aswanth Manoharan   

