# 🏗️ dbt Jaffle Shop Project (DuckDB)

This project is a simple analytics engineering pipeline built using **dbt Core + DuckDB**.

## 🚀 Project Overview
The project simulates a retail data warehouse with:
- Raw data (seeds)
- Staging layer (cleaned models)
- Marts layer (final analytics models)
- Data tests & validation
- Full documentation using dbt docs

## 🧱 Data Models
- Customers
- Orders
- Payments

## 🔄 Data Flow
Raw Seeds → Staging Models → Final Models (Customers & Orders)

## 🧪 Data Quality
Includes:
- Unique tests
- Not null tests
- Accepted values validation
- Relationship integrity checks

## 📊 Tools Used
- dbt Core
- DuckDB
- Git & GitHub
- SQL


## 📊 Data Lineage

<img width="1316" height="602" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/3b16162c-dd65-40a5-8a53-e9e8c54f7482" />


## 📌 How to Run
```bash
dbt seed
dbt run
dbt test
dbt docs generate
dbt docs serve
```
