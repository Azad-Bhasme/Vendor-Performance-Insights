# Vendor-Performance-Insights

This project delivers a comprehensive **Vendor Performance Analysis** by consolidating SQL data, cleaning and transforming it in Python, calculating key performance metrics, and visualizing insights through Power BI. The aim is to help businesses optimize procurement, improve vendor management, and make data-driven decisions.

## 📌 Objective

Automate and streamline the evaluation of vendor performance by:
- Extracting and merging data from multiple relational tables
- Performing exploratory data analysis (EDA) to identify trends and anomalies
- Calculating key metrics such as profit margins, stock turnover, and sales efficiency
- Classifying vendors based on performance insights
- Visualizing findings in an interactive Power BI dashboard

## 🛠️ Tools & Technologies

- **Python 3.x** – Data wrangling & transformation  
- **Pandas** – Data analysis and manipulation  
- **SQLite3** – Querying relational databases  
- **Power BI** – Dashboard creation and visualization  
- **Matplotlib / Seaborn** – Optional visualizations for EDA  
- **Logging** – Tracking process execution and debugging

## 🧩 Project Workflow

### 1. 🧠 Data Ingestion & Transformation (`get_vendor_summary.py`)
- Connects to the SQLite database
- Combines data from purchases, purchase prices, sales, and vendor invoices
- Cleans data and creates new columns: `GrossProfit`, `ProfitMargin`, `StockTurnover`, `SalestoPurchaseRatio`
- Saves the processed summary table for further analysis

### 2. 📊 Exploratory Data Analysis (EDA)
- Checked for null values, outliers, and duplicates
- Analyzed distributions of sales, purchases, and profit metrics
- Investigated correlations between purchase price, sales, profit, and stock turnover
- Identified patterns in vendor and brand performance

### 3. 📈 Vendor Performance Analysis
This phase answers key business questions:
- Which brands require promotional or pricing adjustments due to low sales but high profit margins?
- Which vendors and brands achieve the highest sales performance?
- Which vendors contribute the most to total purchase dollars?
- How much of total procurement is dependent on top-performing vendors?
- Does bulk purchasing reduce unit price, and what is the optimal purchase volume for cost savings?
- How much capital is tied up in unsold inventory per vendor, and which vendors contribute the most?

### 4. 📉 Power BI Dashboard
- Visualizes vendor-level metrics and KPIs
- Interactive charts for sales, margins, stock turnover, and procurement analysis
- Enables informed decision-making for procurement and pricing strategies


  <img width="1303" height="737" alt="Power_bi-Dashboard" src="https://github.com/user-attachments/assets/c0293322-02cb-4b8e-9339-e4adc8ee4b59" />
