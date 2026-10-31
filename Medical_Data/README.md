# Medical Data History Analytics & Dockerized MySQL Database (PRCE-001)

## 📌 Project Overview
A healthcare data engineering and analytics project deployed on containerized MySQL infrastructure. This project evaluates patient clinical histories, admission patterns, attending physician workloads, and demographic health indicators across province boundaries.

---

## 🛠️ Architecture & Technologies
* **Database Engine**: MySQL 5.7 deployed via Docker (`docker run -it --rm mysql:latest`).
* **Containerization**: Custom `Dockerfile` and CLI container management.
* **Analytical SQL**: Complex multi-table joins, subqueries, conditional logic (`CASE WHEN`), window functions, and aggregation functions.

---

## 💡 Key SQL Capabilities & Analysis Solved
1. **Multi-Table Relational Joins**: Connecting `patients`, `admissions`, `doctors`, and `province_names`.
2. **Clinical Metrics & BMI Calculation**: Converting patient height (cm to meters) to compute Body Mass Index ($BMI = \frac{weight}{height^2}$) and categorize obesity status.
3. **Weight Tier Grouping**: Dynamic binning into granular 10kg weight intervals using structured `CASE` statements.
4. **SQL Dialect Optimization**: Resolving `ONLY_FULL_GROUP_BY` strict mode constraints and ranking functions across MySQL versions.

---

## 📂 Project Contents
* `Dockerfile`: Container configuration for spinning up the MySQL environment.
* `13_09_2025 PRCE-001_Medical Data History_Docker Mysql Queries.docx`: Complete compilation of production analytical SQL queries and solutions.
* `13_09_2025 PRCE-001_Medical Data History_Project_Challenges.docx`: Troubleshooting log resolving SQL dialect and grouping constraints.
* `query_output.txt`: Raw CLI terminal output logs from Dockerized MySQL executions.
