# Kimia Farma Final Project – Big Data Analytics

## 📌 Project Overview
This project is the **Final Project** of the Big Data Analytics Project-Based
Internship Program by **Rakamin Academy** in collaboration with **PT Kimia Farma Tbk**.

The objective of this project is to analyze Kimia Farma’s **sales, transactions,
and inventory performance** from **2020 to 2023** using Big Data Analytics tools.
The analysis focuses on generating both **business performance insights** and
**operational insights** to support data-driven decision making.

---

## 📊 Dataset
The dataset consists of:
- Transaction data
- Product data
- Branch data
- Inventory data

All datasets are processed and integrated using **Google BigQuery** as the main
data warehouse.

---

## 🗂 Data Processing & Analytics Tables

### 1. `kf_analytics`
Core analytical table created by integrating transaction, product, and branch data.
This table is used to validate data integration and business metrics.

### 2. `kf_analytics_enriched`
An enriched version of `kf_analytics` with additional time-based features such as:
- year
- month
- month_name
- year_month  

This table is optimized for trend analysis and dashboard visualization.

### 3. `kf_stock_sales_insight`
An advanced analytical table designed to analyze the relationship between
inventory and sales performance, including:
- total stock
- total net sales
- sales per stock unit
- transaction per stock unit  

This table supports operational analysis such as **overstock risk** and
**restock priority** identification.

---

## 📈 Dashboards

### 1️⃣ Business Performance Dashboard
Provides an overview of Kimia Farma’s business performance, including:
- Total Net Sales
- Total Net Profit
- Total Transactions
- Average Transaction Rating
- Sales & profit trends over time
- Geographic performance by province

### 2️⃣ Sales & Inventory Insight Dashboard (Enhanced)
Focuses on operational insights, including:
- Stock vs sales comparison
- Sales efficiency per stock unit
- Overstock risk analysis
- Restock priority analysis

Dashboards are developed using **Looker Studio** with interactive filters for
province, branch category, and date range.

---

## 🛠 Tools & Technologies
- Google BigQuery
- SQL
- Looker Studio
- GitHub

---

## 🎥 Project Explanation Video
[(Insert YouTube link here)](https://drive.google.com/drive/folders/1wiczC7tN0AC4CF_BtuLMZHH1gLeSCm_y?usp=drive_link)

---

## 👤 Author
**Muhammad Abyan Ridhan Siregar**  
Final Project – Kimia Farma Big Data Analytics  
Rakamin Academy
