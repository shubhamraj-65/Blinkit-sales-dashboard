# 📊 Blinkit Sales Dashboard (Power BI Project)

## 🧠 Project Overview
This project is an interactive Power BI dashboard built to analyze Blinkit sales data. It provides insights into sales performance, product categories, outlet analysis, and geographical trends.

The goal of this project is to convert raw sales data into meaningful business insights for decision-making.

---

## 🎯 Objective
To build an interactive Power BI dashboard that analyzes Blinkit sales performance across outlets, product categories, and regions to generate actionable business insights for decision-making.

---

## 📌 Key Business Questions
- Which outlet type generates the highest revenue?
- Which product categories perform best?
- How does sales vary across regions?
- What is the contribution of each outlet type to total sales?

---

## 📊 Dashboard Pages
- Sales Overview
- Product Performance
- Geographic Analysis
- Deep Dive Analysis

---

## 🛠 Tools Used
- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Excel (Dataset)

---

## 🧮 DAX Measures (Business Logic)

This dashboard uses DAX to calculate key business KPIs for analysis.

### Core Measures:
- Total Sales = SUM(Sales[SalesAmount])
- Average Sales = AVERAGE(Sales[SalesAmount])
- Total Items Sold = COUNT(Sales[ItemID])
- Average Rating = AVERAGE(Sales[Rating])

### Business KPIs Derived:
- Sales Contribution % by Outlet Type
- Category-wise Sales Performance
- Outlet Performance Ranking

---

## ⚙️ Key Highlights
- End-to-end data analytics workflow
- Data cleaning using Power Query
- KPI creation using DAX
- Multi-page interactive dashboard
- Business insights generation

---

## 📸 Dashboard Preview

### Sales Overview
![Sales Overview](./Images/sales-overview.png)

### Product Performance
![Product Performance](./Images/product-performance.png)

### Geographic Analysis
![Geographic Analysis](./Images/geographic-analysis.png)

### Filters View
![Filters](./Images/filters.png)

---

## 📊 Business Insights
- Tier 3 locations contributed highest sales, indicating strong rural market demand.
- Regular fat products performed better than low-fat alternatives.
- Medium outlet size generated the highest revenue compared to small and high outlets.
- Supermarket Type 1 was the top performing outlet type.
- Certain product categories consistently outperformed others in terms of sales volume.
- Customer ratings remained stable across all outlet types, indicating consistent service quality.

---

## 👨‍💻 About This Project
This project demonstrates my ability to handle real-world data analytics tasks including data cleaning, modeling, visualization, and business insight generation using Power BI.
