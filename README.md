# 📊 Superstore Sales & Profit Analytics Dashboard

## 🚀 Project Overview

The **Superstore Sales & Profit Analytics Dashboard** is a comprehensive Power BI Business Intelligence solution designed to analyze sales performance, profitability, customer behavior, product contribution, and regional trends. The dashboard transforms raw transactional data into actionable business insights that support strategic decision-making and business growth.

---

## 🎯 Project Objectives

- Analyze overall sales performance.
- Evaluate profitability across products and regions.
- Understand customer purchasing behavior.
- Identify top-performing and underperforming products.
- Assess regional business performance.
- Generate data-driven business recommendations.

---

## 🛠️ Tools & Technologies Used

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Power BI Service
- Data Modeling (Star Schema)

---

## 📂 Dataset Information

- Dataset: Superstore Dataset
- Records: 9,994+
- Columns: 19+

### Key Data Fields

- Order ID
- Order Date
- Customer ID
- Customer Name
- Segment
- Region
- Category
- Sub-Category
- Product Name
- Sales
- Profit
- Quantity
- Discount

---

## 🧹 Data Preparation & Transformation

### Power Query Operations

- Removed duplicate records
- Handled missing values
- Corrected data types
- Renamed columns
- Split columns
- Replaced values where necessary
- Removed unnecessary columns

---

## 🏗️ Data Modeling

Implemented a **Star Schema** model for improved performance and scalability.

### Dimension Tables

- Product Details
- Category Table
- Sub-Category Table
- Year Table
- Abbreviation Table

### Benefits

- Faster DAX calculations
- Better report performance
- Reduced data redundancy
- Easy maintenance

---

## 📈 DAX Measures Created

```DAX
Total Sales = SUM(Data[Sales])

Total Profit = SUM(Data[Profit])

Total Orders = DISTINCTCOUNT(Data[Order ID])

Total Quantity = SUM(Data[Quantity])

Profit Margin % = DIVIDE([Total Profit],[Total Sales],0)

Average Order Value = DIVIDE([Total Sales],[Total Orders],0)

Total Customers = DISTINCTCOUNT(Data[Customer ID])

Average Discount = AVERAGE(Data[Discount])
```

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview

Provides a high-level business summary through KPIs such as:

- Total Sales
- Total Profit
- Profit Margin %
- Total Orders
- Average Order Value
- Top Performing Region

### 2️⃣ Sales Analytics

Analyzes:

- Sales by Region
- Sales by Category
- Sales by Sub-Category
- Sales Trends
- Customer Segment Contribution

### 3️⃣ Profit Analytics

Analyzes:

- Profit by Region
- Profit by Category
- Profit Margin %
- Top & Bottom Profit Products

### 4️⃣ Customer Analytics

Analyzes:

- Customer Contribution
- Customer Segmentation
- Top Customers
- Regional Customer Distribution

### 5️⃣ Product Analytics

Analyzes:

- Product Performance
- Category Contribution
- Sub-Category Analysis
- Discount Impact on Profitability

---

## 📌 Key Insights

- Total Sales reached **$2.29M**.
- Total Profit achieved **$286K**.
- Profit Margin stood at **12.47%**.
- West Region generated the highest sales revenue.
- East Region was the second-highest contributor.
- 5,009 orders were processed from 793 unique customers.
- Consumer Segment generated the largest share of revenue.
- Excessive discounts negatively impacted profitability in some categories.

---

## 💡 Business Recommendations

- Focus marketing efforts on high-performing regions.
- Reduce excessive discounting on low-margin products.
- Strengthen customer retention strategies.
- Promote top-performing products.
- Improve performance in lower-contributing regions.

---

## ✨ Features Implemented

- Drill Down
- Drill Through
- Tooltips
- Dynamic Titles
- Slicers
- Conditional Formatting
- Navigation Buttons
- Bookmarks

---

## 🔗 Project Link

View the complete project here:

[Superstore Sales & Profit Analytics Dashboard](https://github.com/sukrutha912/SUPERSTORE-SALES-PROFIT-ANALYTICS-DASHBOARD.git)

---


## 📷 Dashboard Preview

### Executive Overview
(https://github.com/sukrutha912/SUPERSTORE-SALES-PROFIT-ANALYTICS-DASHBOARD/blob/5e478ef3b765b7d44ff74b8064a1013ff5780463/Executive%20Overview%20Dashboard.png)

### Sales Analytics
(Add Screenshot)

### Profit Analytics
(Add Screenshot)

### Customer Analytics
(Add Screenshot)

### Product Analytics
(Add Screenshot)

---

## 🎓 Key Learnings

- Power Query Transformations
- Data Modeling
- DAX Development
- Dashboard Design
- Business Intelligence Reporting
- Data Storytelling

---

## 📌 Business Impact

- Supports data-driven decision-making.
- Improves sales and profit monitoring.
- Identifies high-performing products and regions.
- Enhances customer-focused strategies.
- Supports revenue growth and profitability improvement.

---

## 👩‍💻 Author

**Bindu Sukrutha Gujjari**

AI & ML Undergraduate  
Malla Reddy University

