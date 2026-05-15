# 🏗️ Jaffle Shop DBT Project (DuckDB)

## 📌 Overview
This is a dbt project built using DuckDB to simulate a simple data warehouse for a retail system.

It includes:
- Raw data (seeds)
- Staging models (cleaned data)
- Marts models (final analytics tables)
- Data tests and validation
- dbt documentation

---

## 🔄 Data Flow
Raw Data → Staging Layer → Final Models

---

## 📊 Models
- customers
- orders
- payments

---

## 🧪 Data Quality
- Unique tests
- Not null tests
- Accepted values tests
- Relationships tests

---

## 🛠️ Tools Used
- dbt Core
- DuckDB
- SQL
- Git & GitHub

---

## 🚀 How to Run

```bash
dbt seed
dbt run
dbt test
dbt docs generate
dbt docs serve

---
Built by Kenzy as part of Data Engineering learning journey.