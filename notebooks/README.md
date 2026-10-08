# 📓 Databricks Analytics Notebooks

This folder contains six Databricks notebooks documenting the end-to-end analytical workflow for **Project #4 — Supply Chain Planning & Operations Intelligence**.

The notebooks demonstrate how manufacturing S&OP planning data was ingested, transformed, validated, modeled, and analyzed using **Databricks, PySpark, SQL, and Python optimization**.

## ⚙️ Notebook Workflow 

| Notebook | Purpose |
|---|---|
| [01_Load_Raw_SOP_Source](01_Load_Raw_SOP_Source.ipynb) | Ingest and structure raw Excel planning data into 21 Bronze Delta tables. |
| [02_Transform_Clean_SOP_Data](02_Transform_Clean_SOP_Data.ipynb) | Standardize, clean, and transform source data into the Silver layer. |
| [03_Validate_SOP_Data_Quality](03_Validate_SOP_Data_Quality.ipynb) | Perform data-quality validation, reconciliation, and integrity checks. |
| [04_Build_Gold_Data_Warehouse](04_Build_Gold_Data_Warehouse.ipynb) | Develop 12 analysis-ready Gold tables using dimensional modeling. |
| [05_Supply_Chain_SQL_Analytics](05_Supply_Chain_SQL_Analytics.ipynb) | Analyze demand, capacity, planning constraints, and operational relationships using SQL. |
| [06_Supply_Chain_Python_Analytics](06_Supply_Chain_Python_Analytics.ipynb) | Apply Python linear programming to evaluate alternative workload allocation and optimization scenarios. |

## 🏗️ Analytical Architecture

**21 Bronze Tables → 21 Silver Tables → 12 Gold Analytical Tables → 4 Optimization Scenario Tables → Power BI Decision-Support Dashboard**

The Gold analytical model includes **4 dimension tables, 4 fact tables, and 4 bridge tables**.

The optimization model contains four scenario tables:

- `machine_period_summary`
- `scenario_allocations`
- `scenario_assumptions`
- `scenario_summary`

## 🎯 Analytical Value

This workflow demonstrates the ability to transform complex source data into validated analytical models, apply SQL and Python for diagnostic and prescriptive analysis, and support business decisions through interactive reporting.

**Note:** The notebooks are exported for technical review. Executing the full pipeline requires a compatible Databricks environment, source data, and supporting Delta tables.

---

[⬅️ Back to Main Project README](../README.md)
