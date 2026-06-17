# 📱 Mobile Sales Analytics Dashboard

## 📌 Project Overview

This project delivers an interactive sales analytics solution for a mobile retail business, enabling stakeholders to monitor sales performance, transaction volumes, product demand, payment methods, and geographic sales distribution. The dashboard supports inventory optimization and data-driven market expansion decisions.

---

## 🎯 Business Problem

Leadership required a centralized analytics platform to track device sales, transaction volumes, geographic performance, and payment trends across multiple regions. The goal was to identify high-performing markets, best-selling products, and customer purchasing behaviors to improve inventory planning and sales strategy.

---

## 🛠️ Tools & Technologies

* Power BI
* Power Query (ETL)
* DAX
* Geographic Mapping
* Data Modeling

---

## 📊 Key Performance Indicators (KPIs)

| KPI                 | Value |
| ------------------- | ----- |
| Total Sales         | $769M |
| Total Quantity Sold | 19K   |
| Total Transactions  | 4K    |
| Average Sales Value | $40K  |

---

## 📈 Dashboard Features

### Executive Overview

* Sales Performance Monitoring
* Transaction Analysis
* Revenue Trends

### Geographic Analysis

* Region-wise Sales Distribution
* City-Level Performance Mapping
* Market Concentration Analysis

### Product Analysis

* Best-Selling Mobile Devices
* Revenue Contribution by Product
* Quantity Sold by Brand

### Payment Analysis

* Payment Method Distribution
* Transaction Channel Performance
* Customer Payment Preferences

### Interactive Filters

* Brand
* Mobile Model
* City
* Payment Method
* Date Range

---

## 🔍 Key Insights

### 1. Geographic Concentrators

* North and Central India emerged as the strongest sales regions.
* Major transaction hubs include **Delhi** and **Lucknow**, contributing significantly to overall sales volume.

### 2. Product Revenue Drivers

The following models generated the highest revenue:

* iPhone SE
* OnePlus Nord
* Galaxy Note 30

These devices consistently outperformed other products in both sales value and transaction volume.

### 3. Payment Method Analysis

Customer payment preferences are highly diversified:

* Credit Card: **26.25%**
* Debit Card: **25.03%**
* Remaining transactions distributed across UPI, Cash, and Digital Wallets.

### 4. Inventory Optimization Opportunities

High-demand products and regions can be prioritized for stock allocation, reducing inventory shortages and improving customer satisfaction.

---

## 📌 DAX Measures Used

```DAX
Total Sales =
SUM(Sales[Sales_Amount])

Total Quantity =
SUM(Sales[Quantity])

Total Transactions =
DISTINCTCOUNT(Sales[Transaction_ID])

Average Sales Value =
DIVIDE([Total Sales], [Total Transactions])
```
---

## 🚀 Business Impact

* Improved visibility into regional sales performance.
* Enabled data-driven inventory planning and demand forecasting.
* Identified top-selling devices and revenue-generating products.
* Enhanced understanding of customer payment behavior.
* Supported strategic decision-making through interactive visual analytics.

---

