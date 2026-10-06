# Supermarket Sales & Business Analytics Dashboard

## 📊 Project Overview

The **Supermarket Sales & Business Analytics Dashboard** is an interactive Power BI project designed to analyze sales performance, profitability, customer behavior, branch performance, product categories, cities, and payment methods.

The dashboard provides an executive-level overview of business performance using interactive KPIs, slicers, charts, and time-based analysis.

## 🎯 Project Objectives

- Analyze overall sales and profitability
- Track total orders and customers
- Analyze monthly sales and profit trends
- Compare sales performance across branches and cities
- Analyze sales by product category
- Understand customer payment method preferences
- Provide interactive filtering for business analysis

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Data Modeling**

## 📌 Key KPIs

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Total Quantity
- Profit Margin %

## 📈 Dashboard Features

- Interactive Year slicer
- Interactive City slicer
- Interactive Category slicer
- Interactive Payment Method slicer
- Monthly Sales & Profit Trend
- Sales by Branch
- Sales by Category
- Sales by Payment Method
- Sales by City
- KPI cards for business performance

## 🧮 DAX Measures

### Total Sales

```DAX
Total Sales =
SUM(Sales_Data[Sales])

Total Profit =
SUM(Sales_Data[Profit])

Total Orders =
DISTINCTCOUNT(Sales_Data[Order ID])

Total Customers =
DISTINCTCOUNT(Sales_Data[Customer ID])

Total Quantity =
SUM(Sales_Data[Quantity])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)

📅 Data Model
A dedicated Date Table was created using DAX to support time-based analysis.
The Date Table includes:
- Year
- Month
- Month Number
- Month Year
- Quarter
- Day
- Day Name
The Date Table is related to the Sales_Data table using the Order Date field.

📊 Key Business Insights
The dashboard enables users to identify:
- Monthly sales and profit trends
- High-performing branches
- Category-wise sales contribution
- City-wise sales performance
- Customer payment preferences
- Overall sales and profitability performance

📷 Dashboard Preview
 
📁 Project Files
- Supermarket-Sales-Business-Analytics-Dashboard.pbix
- README.md
- dashboard.png

👩‍💻 Author
Vaddella Sai Harshitha
Computer Science Graduate | Aspiring Data Analyst / Python Developer
