# 🛒 RetailMart Data Engineering Project

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Python](https://img.shields.io/badge/python-3.12+-blue)
![Databricks](https://img.shields.io/badge/platform-Databricks-orange)
![Apache Spark](https://img.shields.io/badge/engine-Apache%20Spark-red)
![Architecture](https://img.shields.io/badge/architecture-Medallion-lightgrey)
![License](https://img.shields.io/badge/license-MIT-blue)

## Overview

RetailMart Data Engineering Platform is an end-to-end retail analytics project built using **Databricks Free Edition**, **PySpark**, **Delta Lake**, **SQL**, and **Python**. The solution follows the **Medallion Architecture (Bronze → Silver → Gold)** to ingest, clean, transform, and analyze retail data from multiple CSV sources.

The platform demonstrates modern data engineering practices including data cleaning, schema enforcement, business transformations, SQL analytics, and scalable data processing.

---

## Architecture

```text
CSV Files
    │
    ▼
Bronze Layer (Raw)
    │
    ▼
Silver Layer (Cleaned & Validated)
    │
    ▼
Gold Layer (Business Ready)
    │
    ▼
SQL Analytics & Business Insights
```

## Medallion Layers

| Layer | Description |
|------|-------------|
| Bronze | Raw data ingestion from CSV files |
| Silver | Data cleaning, validation, deduplication, datatype conversion |
| Gold | Business KPIs, reporting datasets and SQL analytics |

## Technology Stack

- Python
- Apache Spark (PySpark)
- Databricks Free Edition
- Delta Lake
- SQL
- Pandas
- NumPy
- Git & GitHub
- Jupyter Notebook

## Dataset

The project processes retail business data including:

- Customers
- Orders
- Products
- Sales
- payments

## Features

- End-to-end ETL pipeline
- Medallion Architecture
- Data validation
- Missing value handling
- Duplicate removal
- SQL analytics
- Business KPI generation
- GitHub project structure
- Modular notebooks

## Project Structure

```text
RetailMart/
│
├── data/
    ├── raw/
    ├── Bronze/
    ├── Silver/
    ├── Gold/

├── Databricks/
│   ├── 01_Data_ingestion.ipynb
│   ├── 02_Bronze.ipynb
│   ├── Silver_orders.ipynb
|   ├── silver_customer.ipynb
|   ├── silver_order_items.ipynb
|   ├── silver_products.ipynb
|   ├── silver_payments.ipynb
│   ├── 04_Gold.ipynb
│   └── 
├── sql/
|    ├── sql_analysis.ipynb
├── requirements.txt
├── retailmart_project_report
└── README.md
```

## Installation

```bash
git clone <repository-url>
cd RetailMart
pip install -r requirements.txt
```

## Running the Project

<img width="1492" height="435" alt="Retal_ETL_pipeline" src="https://github.com/user-attachments/assets/527dcf55-e0f5-4f0f-9c11-22cdb2407f87" />





1. 01_Data_Load
2. 02_Bronze
3. 03_Silver
4. 04_Gold
5. 05_SQL_Analysis

## Data Quality Checks

- Duplicate removal
- Missing value handling
- Invalid date correction
- Data type validation
- Null checks

## Business KPIs

- Total Revenue
- Total Orders
- Total Customers
- Product Performance
- Monthly Sales Trend
- Category-wise Revenue
- Customer Purchase Analysis

## SQL Analysis

Example analyses include:

- Top-selling products
- Monthly revenue
- Customer order frequency
- Revenue by category
- Sales trends

## Future Enhancements

- Real-time streaming
- Apache Airflow orchestration
- CI/CD with GitHub Actions
- Power BI integration
- Azure Data Lake
- Automated monitoring

## Dashboard

<img width="1512" height="695" alt="Screenshot 2026-07-12 105004" src="https://github.com/user-attachments/assets/c4c9d3a1-7dda-46f1-a1eb-7515aa0163eb" />
<img width="1572" height="732" alt="image" src="https://github.com/user-attachments/assets/d30dae25-5a5d-4eaf-b346-55e6eaa966d3" />



## Author

**Raj Kumar**

Data Engineering Project using Databricks, PySpark, Delta Lake, SQL, and Python.
