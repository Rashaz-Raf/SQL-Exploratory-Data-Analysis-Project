# 🧠 Exploratory Data Analysis

This project delivers a full-stack **data analytics solution** using SQL to perform **Exploratory Data Analysis (EDA)** on a sales dataset.

It is structured for modular development, enabling seamless database initialization, analytical processing, and report generation using clean SQL workflows.

---

## 📦 Dataset Overview

The dataset is structured into a **star schema**:

- `gold.dim_customers.csv` – Customer details (demographics, IDs)
- `gold.dim_products.csv` – Product details (categories, pricing)
- `gold.fact_sales.csv` – Sales transactions (orders, dates, revenue)

---

### 🔍 Exploratory Data Analysis (EDA)

Run: `scripts/exploratory_data_analysis.sql`
This file aggregates all base-level analysis scripts under one file.

Key Modules:

- date_analysis.sql – Order timelines and customer birthdate ranges

- dimension_analysis.sql – Countries, categories, product groups

- magnitude_analysis.sql – Total sales, quantities, customer counts

- measure_analysis.sql – Averages, percentages, price metrics

- ranking_analysis.sql – Top-performing customers & products

---

## 📊 Business Insights Enabled

✔️ Track customer and product performance over time  
✔️ Identify high-value customers and products  
✔️ Segment customers by behavior and value  
✔️ Detect seasonal sales patterns  
✔️ Benchmark performance against historical trends

---
