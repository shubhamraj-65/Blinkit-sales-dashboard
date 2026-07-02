# 📊 Blinkit Sales Dashboard (Power BI Project)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Business%20Logic-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power_Query-Data%20Cleaning-green?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

## 🚀 Project Highlights

- Designed a fully interactive multi-page Power BI dashboard.
- Cleaned and transformed raw sales data using Power Query.
- Created reusable DAX measures for business KPIs and performance tracking.
- Developed dynamic filters for month, city, and delivery type analysis.
- Built interactive visualizations for sales, products, geography, and customer behavior.
- Identified key business trends and generated actionable recommendations.
- Applied data storytelling techniques to present insights in a clear and business-friendly manner.

---

## 🧠 Project Overview
This project is an interactive Power BI dashboard built to analyze Blinkit sales data. It provides insights into sales performance, product categories, outlet analysis, and geographical trends.

The goal of this project is to convert raw sales data into meaningful business insights for decision-making.

---

## 🎯 Objective
To build an interactive Power BI dashboard that analyzes Blinkit sales performance across outlets, product categories, and regions to generate actionable business insights for decision-making.

---

## 📌 Key Business Questions

- Which cities contribute the highest revenue to Blinkit's overall sales?
- Which product categories generate the maximum sales and customer demand?
- What are the monthly sales trends, and are there any seasonal patterns?
- Which payment methods are most preferred by customers?
- How does delivery type (Standard vs Express) impact sales performance?
- Which products contribute the highest revenue?
- Which sellers consistently achieve the best sales performance?
- How do customer ratings vary across products and sellers?
- Which categories perform well across different delivery methods?
- What business opportunities can be identified to improve sales and customer experience?

---

## 📊 Dashboard Pages

| Dashboard | Description |
|-----------|-------------|
| 📈 Sales Overview | Business KPIs, Sales Trend, Payment Distribution |
| 🛒 Product Performance | Top Products, Category Analysis, Product Revenue |
| 🌍 Geographic Analysis | City-wise Sales Performance |
| 🔍 Deep Dive Analysis | Seller Performance, Delivery Type Analysis |

---

## 🛠 Tools Used
- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Excel (Dataset)

---

## 📂 Project Structure

```
Blinkit-Sales-Dashboard/
│
├── Blinkit_Sales_Dashboard.pbix
├── README.md
│
├── Dataset/
│   └── Blinkit_Data.xlsx
│
├── Images/
│   ├── sales-overview.png
│   ├── product-performance.png
│   ├── geographic-analysis.png
│   └── filters.png
│
├── DAX/
│   └── DAX_Measures.md
│
├── Power-Query/
│   └── PowerQuery_Steps.md
│
└── Documentation/
    └── Project_Documentation.md
```
---

## 🧮 DAX Measures (Business Logic)

This dashboard uses DAX (Data Analysis Expressions) to create dynamic KPIs and business metrics that enable interactive analysis and data-driven decision-making.

### Core Measures

- **Total Sales** – Calculates the total revenue generated from all orders.
- **Average Sales** – Calculates the average revenue per order.
- **Total Orders** – Counts the total number of completed orders.
- **Average Customer Rating** – Calculates the overall customer satisfaction score.

### DAX Formulas

```DAX
Total Sales =
SUM(Sales[SalesAmount])

Average Sales =
AVERAGE(Sales[SalesAmount])

Total Orders =
COUNT(Sales[OrderID])

Average Rating =
AVERAGE(Sales[Rating])
```
---

### Business KPIs Derived

- Sales Contribution (%) by Outlet Type
- Category-wise Sales Performance
- Outlet Performance Ranking
- Monthly Sales Trend Analysis

---

## 📸 Dashboard Preview

### 📈 1. Sales Overview

This page presents an overall summary of business performance, including KPIs, monthly sales trends, payment distribution, and product category analysis.

**Key Components**
- Total Sales
- Total Orders
- Average Sales
- Average Rating
- Monthly Sales Trend
- Payment Method Distribution
- Product Category Distribution

![Sales Overview](./Images/sales-overview.png.jpeg)

---

### 🛒 2. Product Performance

This page analyzes product-level performance to identify top-selling products and high-performing categories.

**Key Components**
- Top Selling Products
- Product Category Analysis
- Product Performance Table
- Category-wise Revenue

![Product Performance](./Images/product-performance.png.jpeg)

---

### 🌍 3. Geographic Analysis

This page provides city-wise sales analysis to identify the best-performing regions and geographical trends.

**Key Components**
- City-wise Sales
- Top Performing Cities
- Regional Performance
- Sales Comparison by Location

![Geographic Analysis](./Images/geographic-analysis.png.jpeg)

---

### 🔍 4. Deep Dive Analysis

This page offers detailed insights into seller performance, delivery type analysis, and product hierarchy.

**Key Components**
- Seller Performance
- Delivery Type Analysis
- Product Performance Tree
- Detailed Business Analysis

![Deep Dive Analysis](./Images/filters.png.jpeg)

---

## 📊 Business Insights

1. Bengaluru emerged as the highest revenue-generating city, contributing approximately ₹40K in sales, making it the strongest performing market.

2. Total sales reached approximately ₹147K across 923 orders, with an average order value of ₹159.57 and an average customer rating of 4.36, indicating consistent customer satisfaction.

3. Grocery and Dairy categories generated the highest revenue among all product categories, while Bakery contributed the lowest share of total sales.

4. Apple 1kg was identified as the best-selling product, making it a key revenue-driving SKU.

5. UPI and Cash were the most preferred payment methods, together accounting for the majority of customer transactions.

6. Sales showed noticeable monthly fluctuations, with the highest sales recorded in Month 5 and a decline observed in Month 6, indicating possible seasonal demand patterns.

7. Standard delivery contributed significantly more revenue than Express delivery, suggesting customers preferred the regular delivery option.

8. Freshfarm recorded the highest seller revenue among all sellers, while customer ratings remained consistently above 4.3 across major sellers, reflecting stable service quality.

9. Product category performance varied by delivery type, with Grocery and Dairy maintaining strong sales across both Standard and Express deliveries.

10. Geographic analysis highlighted Bengaluru as the top-performing city, followed by Delhi and Jaipur, providing clear opportunities for region-specific marketing and inventory planning.

---

## 💡 Business Recommendations

1. Increase inventory availability for Grocery and Dairy products to meet high customer demand.
2. Expand marketing campaigns in Bengaluru and other top-performing cities to maximize revenue.
3. Investigate the sales decline in Month 6 and identify potential seasonal or operational factors.
4. Encourage digital payment adoption by offering incentives on UPI transactions.
5. Improve sales performance of lower-performing categories such as Bakery through promotional offers and bundled discounts.

---

## 💼 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- Power Query
- Data Visualization
- Business Intelligence
- KPI Development
- Dashboard Design
- Data Storytelling

---

## 👨‍💻 About This Project

This project demonstrates an end-to-end Business Intelligence workflow using Power BI. Starting from raw sales data, I performed data cleaning and transformation using Power Query, built analytical measures with DAX, and designed an interactive dashboard to uncover meaningful business insights.

The dashboard enables users to monitor sales performance, evaluate product and seller performance, analyze regional trends, understand customer purchasing behavior, and support data-driven business decisions through interactive visualizations and KPIs.

---

## 📬 Connect With Me

If you have any feedback or suggestions regarding this project, feel free to connect with me on LinkedIn or explore more projects on my GitHub profile.

⭐ If you found this project useful, consider giving it a star.
Made with ❤️ using Microsoft Power BI.
