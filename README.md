# Vendor-Performance-Insights

This project conducts a comprehensive **Vendor-Performance-Insights** by integrating multiple SQL data sources, cleaning and transforming data in Python, calculating key performance metrics, and visualizing actionable insights in Power BI. The goal is to support data-driven decisions for procurement optimization and vendor management.

## 📌 Objective

To automate and streamline vendor performance evaluation by:
- Extracting and merging data from multiple relational tables
- Performing exploratory data analysis (EDA) to understand trends and anomalies
- Calculating profitability, stock turnover, and sales efficiency metrics
- Classifying vendors based on performance and margin insights
- Visualizing results through an interactive Power BI dashboard for business decisions

## 🛠️ Tools & Technologies

- **Python 3.x** – Data wrangling and transformation  
- **Pandas** – Data manipulation and analysis  
- **SQLite3** – Querying and aggregating relational data  
- **Power BI** – Interactive data visualization and dashboard creation  
- **Matplotlib / Seaborn** – Optional EDA visualizations  
- **Logging** – Debugging and traceability of scripts

## 🧩 Project Workflow

### 1. 🧠 Data Ingestion & Transformation (Script: `get_vendor_summary.py`)
- Connects to the SQLite database
- Merges tables: purchases, purchase prices, sales, and vendor invoices
- Cleans data and creates calculated columns: `GrossProfit`, `ProfitMargin`, `StockTurnover`, `SalestoPurchaseRatio`
- Stores the processed summary table for analysis

### 2. 📊 Exploratory Data Analysis (EDA)
- Checked for nulls, outliers, and duplicates
- Analyzed distributions of sales, purchase, and margin metrics
- Investigated correlations between purchase price, sales, profit, and stock turnover
- Identified trends and patterns in vendor and brand performance

### 3. 📈 Vendor Performance Analysis
The analysis answers key business questions:
- Which brands require promotional or pricing adjustments due to low sales but high profit margins?
- Which vendors and brands achieve the highest sales performance?
- Which vendors contribute most to total purchase dollars?
- How much of total procurement is dependent on top-performing vendors?
- Does bulk purchasing lower unit price, and what is the optimal volume for cost savings?
- How much capital is tied up in unsold inventory per vendor, and which vendors contribute the most?

### 4. 📉 Power BI Dashboard
- Visualizes vendor-level metrics and KPIs
- Provides interactive charts for sales, margins, stock turnover, and purchase analysis
- Helps business teams make informed procurement and pricing decisions
  <img width="1303" height="737" alt="Power_bi-Dashboard" src="https://github.com/user-attachments/assets/c0293322-02cb-4b8e-9339-e4adc8ee4b59" />
