# Azure Cloud Data Warehouse & ETL Pipeline Architecture

## 📌 Project Overview
This capstone project implements an end-to-end enterprise Data Warehouse using Microsoft Azure cloud data services. The pipeline ingests 7 OLTP source tables, performs schema normalization and business-logic transformations, and populates analytical schemas in Azure SQL Database for executive reporting.

---

## 🏗️ Architecture & Data Flow

```text
OLTP Relational Tables (7 CSVs)
              ↓
Raw Layer: Azure Blob Storage
              ↓
Transformation & Staging: Azure Data Factory (ADF Data Flows)
              ↓
Analytical Serving Layer: Azure SQL Database
              ↓
Business Intelligence & Queries: Azure Data Studio / Power BI
```

### 1. Ingested OLTP Source Tables
* `country.csv`: Country master codes and geographic regional metadata.
* `customers.csv`: Customer identification, contact information, and billing geography.
* `dept.csv`: Corporate department hierarchies and locations.
* `emp.csv`: Employee master records, managerial reporting structures, and salaries.
* `orders.csv`: Transactional sales order records, timestamps, and customer mappings.
* `products.csv`: Product catalog, pricing, and category classifications.
* `salgrade.csv`: Compensation and salary grade tier definitions.

---

## 🛠️ Azure Services Implemented
1. **Azure Resource Groups**: Logical container organizing interconnected cloud resources.
2. **Azure Blob Storage**: Scalable cloud object storage hosting the raw CSV landing zone.
3. **Azure Data Factory (ADF)**: Orchestration engine automating copy activities, schema mapping, and pipeline scheduling.
4. **Azure SQL Database & Server**: Managed relational cloud database serving analytical queries.
5. **Azure Data Studio**: Modern client tool for database exploration, query optimization, and visualization.

---

## 📂 Repository Contents
* `Data Warehouse_Project_Approach.docx`: Detailed architecture design and implementation approach document.
* `OLTP Tables/`: Directory containing all 7 source CSV files.
* `Azure ETL services/`: Service configuration screenshots, resource topologies, and query view documentation (`Azure Database Query view_Sept 27_2025.pdf`).
* `Azure_Query_Screenshots/`: Validated query execution screenshots verifying analytical transformation outputs.
