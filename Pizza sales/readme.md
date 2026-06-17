# 🍕 Pizza Sales Analytics Dashboard

## 📌 Project Overview

This project analyzes pizza sales data to uncover customer ordering behavior, product performance, and revenue-driving trends. Using Power BI and advanced DAX calculations, the dashboard provides actionable insights to optimize operations, inventory planning, and marketing strategies.

---

## 🎯 Business Problem

A global pizza chain lacked visibility into peak ordering periods, customer purchase patterns, pizza sizing preferences, and menu performance. The objective was to create an analytics solution that would help stakeholders make data-driven operational and business decisions.

---

## 🛠️ Tools & Technologies

* Power BI
* Power Query (ETL)
* Advanced DAX
* Time Intelligence Functions
* Python (Data Profiling & Exploration)

---

## 📊 Key Performance Indicators (KPIs)

| KPI                      | Value |
| ------------------------ | ----- |
| Total Revenue            | $329K |
| Average Order Value      | $38   |
| Total Pizzas Sold        | 20K   |
| Total Orders             | 9K    |
| Average Pizzas per Order | 2.33  |

---

## 📈 Dashboard Features

### Executive Overview

* Revenue performance tracking
* Order volume monitoring
* Customer purchase behavior

### Time-Based Analysis

* Hourly order trends
* Daily order distribution
* Weekly sales performance

### Product Performance

* Best-selling pizza categories
* Revenue contribution by product
* Pizza size analysis

### Interactive Filters

* Date Range
* Pizza Category
* Pizza Size
* Order Time

---

## 🔍 Key Insights

### 1. Peak Demand Windows

* Customer orders significantly increase during **Friday and Saturday evenings**.
* **Wednesday** emerged as the highest-volume weekday with **1,227 total orders**.

### 2. Pizza Size Preferences

* Large pizzas dominate customer demand.
* Large-sized pizzas contribute **45.89%** of total pizza sales volume.

### 3. Category Performance

* The **Classic Pizza** category is the top-selling category.
* Total units sold: **5,907 pizzas**.

### 4. Revenue Optimization Opportunities

* Peak-hour ordering patterns indicate opportunities for staffing and inventory optimization.
* High-performing categories can be prioritized in promotions and marketing campaigns.

---

## 📌 DAX Measures Used

```DAX
Total Revenue =
SUM(Sales[Total_Price])

Total Orders =
DISTINCTCOUNT(Sales[Order_ID])

Average Order Value =
DIVIDE([Total Revenue], [Total Orders])

Average Pizzas Per Order =
DIVIDE([Total Pizzas Sold], [Total Orders])
```

---

## 🚀 Business Impact

* Identified peak ordering periods for workforce planning.
* Improved understanding of customer purchasing behavior.
* Highlighted top-performing products and categories.
* Enabled data-driven decisions for inventory management and promotional campaigns.

---

