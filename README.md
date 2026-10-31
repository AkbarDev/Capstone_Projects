# Capstone Projects Portfolio

[![Author](https://img.shields.io/badge/Author-AkbarDev-blue.svg)](https://github.com/AkbarDev)
[![Domain](https://img.shields.io/badge/Domain-Data%20Engineering%20%26%20Analytics-green.svg)](#)
[![Stack](https://img.shields.io/badge/Stack-Azure%20%7C%20ADF%20%7C%20Docker%20%7C%20MySQL%20%7C%20PySpark-orange.svg)](#)

A centralized repository containing end-to-end Data Engineering, Cloud Warehousing, and Advanced Analytics capstone projects. Each project represents a real-world enterprise implementation covering data ingestion, pipeline orchestration, distributed processing, relational data modeling, and business analytics.

---

## 📂 Project Directory Map

| Project Directory | Domain / Focus | Key Tech Stack | Description |
|---|---|---|---|
| [`Azure_Anti_projects/`](./Azure_Anti_projects/) | Cloud Data Warehousing & ETL | Azure Blob Storage, Azure Data Factory (ADF), Azure SQL, Azure Data Studio | End-to-end data warehouse integrating 7 OLTP source tables into analytical star schemas using Azure cloud services. |
| [`Customer_Spending_Analysis/`](./Customer_Spending_Analysis/) | Retail & Customer Intelligence | Python, PySpark, Jupyter, Pandas, Matplotlib | Demographic customer clustering, annual income vs. spending score distributions, and PySpark pipeline analysis (PRCE-003). |
| [`Medical_Data/`](./Medical_Data/) | Containerized Database & Healthcare Analytics | Docker, MySQL 5.7, SQL, Relational Modeling | Dockerized MySQL relational database environment analyzing patient admissions, doctor assignments, and BMI/obesity distributions (PRCE-001). |

---

## 🚀 Projects Overview

### 1. [Azure Cloud Data Warehouse & ETL Pipeline Architecture](./Azure_Anti_projects/)
* **Objective**: Ingest, cleanse, and transform 7 distinct OLTP relational datasets (`country`, `customers`, `dept`, `emp`, `orders`, `products`, `salgrade`) into a centralized cloud data warehouse.
* **Architecture**:
  * **Raw Layer**: Azure Blob Storage (CSV ingestion).
  * **Staging & Transformation Layer**: Azure Data Factory (ADF) automated Data Flows.
  * **Serving & Analytical Layer**: Azure SQL Database with Azure Data Studio connectivity.

### 2. [Mall Customer Spending & Demographic Segmentation](./Customer_Spending_Analysis/)
* **Objective**: Segment retail consumers based on demographic variables (age, gender, annual income) and spending scores to drive targeted merchandising strategies.
* **Tech Highlights**: PySpark distributed processing, exploratory data analysis (EDA), anomaly detection, and clustering visualization.

### 3. [Medical Data History Analytics & Dockerized MySQL](./Medical_Data/)
* **Objective**: Deploy containerized MySQL database infrastructure to execute complex healthcare analytical queries on patient admission trends, province-level demographics, and clinical metrics.
* **Tech Highlights**: Docker containerization (`docker run -it --rm mysql:latest`), advanced SQL aggregations, conditional `CASE` statements, window functions, and BMI health score categorization.

---

## 👤 Author
**Shaik Akbar Basha**  
* GitHub: [@AkbarDev](https://github.com/AkbarDev)  
* Portfolio: [TrendGrid / SnapFacts](https://www.snapfacts.in)
