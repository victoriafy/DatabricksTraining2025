# Databricks Training 2025

# 🛍️ E-Commerce Order Enrichment Training (PySpark + Delta Lake on Databricks)

This repository contains a beginner-friendly Databricks training project designed to teach fundamental data engineering concepts using **PySpark** and **Delta Lake**.

## 🚀 Project Scenario

You are working as a data engineer at an e-commerce company.  
The company already stores order data in a Delta table, but customer information is delivered as a new CSV file. Your mission:

1. Ingest the customer dataset
2. Join it with the existing Delta orders
3. Overwrite the original Delta table with enriched data
4. Perform analytical queries
5. Explore Delta Lake versioning and rollback features

---

## 📁 Contents

- `orders.csv` — Main dataset (~50k rows of order data)
- `customers.csv` — Supplementary dataset (~10k rows of customer info)
- `DatabricksPractice.ipynb` — Full guided notebook with instructions, code, and exercises

---

## 📚 Learning Objectives

By the end of this project, learners will be able to:

- Read/write Delta tables using PySpark
- Load CSV files from DBFS
- Perform `join` operations between datasets
- Run aggregations (`groupBy`, `count`, `sum`, etc.)
- Use Delta Lake's time travel and rollback features
- Practice using real-world data pipelines

---

## 💡 Bonus Challenges (included in the notebook)

- Find the most popular product category
- Identify top spending customers
- Extract temporal insights (e.g., peak order month)
- Create new columns using conditional logic
- Count high-value orders per region

