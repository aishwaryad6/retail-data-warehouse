# 📊 Retail Data Warehouse & Reporting System

This project demonstrates the design and implementation of a modern **data warehouse** for retail sales and customer data. It uses **SQL Server** with Medallion Architecture (Bronze, Silver, Gold layers) to process raw ERP and CRM data into analytics-ready models, enabling **reporting and business insights**.

---

## 🏗️ Data Architecture

The architecture follows a layered design:

- **Bronze Layer** – Ingests raw ERP/CRM data (CSV → SQL Server).  
- **Silver Layer** – Cleanses, standardizes, and prepares data for analysis.  
- **Gold Layer** – Star schema with fact and dimension tables for reporting and dashboards.

---

## 🚀 Features

- Built **ETL pipelines** to extract, transform, and load ERP + CRM datasets.  
- Designed **star schema models** optimized for analytical queries.  
- Implemented **data quality checks** (deduplication, type consistency).  
- Delivered **SQL-based reports** for sales trends, customer behavior, and product performance.

---

## 📊 Analytics & Reporting

- Analyzed **customer behavior** (retention, churn, segmentation).  
- Generated **sales trends** and product performance metrics.  
- Produced dashboards in **Power BI/Tableau** for business stakeholders.

---

## 🛠️ Tech Stack

- **Database**: SQL Server  
- **Data Modeling**: Star Schema (Fact & Dimension Tables)  
- **ETL**: SQL Scripts (Bronze → Silver → Gold)  
- **Visualization**: Power BI, Tableau  
- **Tools**: SQL Server Management Studio (SSMS), Draw.io

---

## 📂 Repository Structure

```bash
retail-data-warehouse/
│
├── datasets/                  # Sample ERP and CRM datasets (CSV)
├── docs/                      # Documentation and architecture diagrams
│   ├── data_architecture_Diagram.png
│   ├── data_models.png
│   └── data_catalog.md
├── scripts/                   # SQL scripts for ETL and transformations
│   ├── bronze/
│   ├── silver/
│   └── gold/
├── tests/                     # Validation queries & test scripts
└── README.md                  # Project overview


---

## 🎯 Key Outcomes

- Reduced reporting latency by consolidating ERP + CRM data into a single warehouse.  
- Delivered **actionable insights** for customer segmentation and product sales.  
- Established a **scalable foundation** for future BI and analytics initiatives.

---
