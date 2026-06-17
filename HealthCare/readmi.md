# 🏥 Healthcare Performance Analytics Dashboard

## 📌 Project Overview

This project provides a comprehensive healthcare analytics solution designed to monitor hospital operations, financial performance, patient demographics, and departmental profitability. The dashboard enables healthcare executives to make data-driven decisions regarding resource allocation, capacity planning, and revenue optimization.

---

## 🎯 Business Problem

Hospital executives needed a centralized analytics platform to monitor financial health, patient admissions, demographic trends, and operational efficiency. The objective was to gain visibility into revenue generation, profitability, patient flow, and departmental performance to improve healthcare delivery and resource management.

---

## 🛠️ Tools & Technologies

* Power BI
* Data Modeling
* Relational Star Schema
* DAX Measures
* Power Query

### Data Model

* Fact_Patient_Visit
* Dim_Patient
* Dim_Hospital
* Dim_Department
* Dim_Date

---

## 📊 Key Performance Indicators (KPIs)

| KPI                    | Value     |
| ---------------------- | --------- |
| Total Patients         | 1,000+    |
| Total Revenue          | $44M      |
| Total Cost             | $28M      |
| Net Profit             | $16M      |
| Average Length of Stay | 5.71 Days |

---

## 📈 Dashboard Features

### Executive Overview

* Revenue, Cost, and Profit Monitoring
* Patient Admission Tracking
* Hospital Performance Summary

### Financial Analysis

* Department-wise Revenue
* Cost vs Revenue Analysis
* Profitability Assessment

### Patient Demographics

* Age Group Distribution
* Gender Analysis
* Admission Trends

### Operational Metrics

* Average Length of Stay
* Patient Volume Tracking
* Capacity Utilization Indicators

### Interactive Filters

* Hospital
* Department
* Gender
* Age Group
* Admission Date

---

## 🔍 Key Insights

### 1. Department Profitability

* Diagnostics and Cardiology emerged as the most profitable departments.
* These departments act as the primary revenue drivers for the healthcare network.

### 2. Age & Gender Analysis

* Female patients account for **53.3%** of total admissions.
* The **18–30 age group** represents the largest patient segment, contributing **29.67%** of overall admissions.

### 3. Hospital Performance Ranking

* Max Hospital generated the highest revenue across the network.
* Total revenue contribution exceeded **$9.1M**.

### 4. Operational Efficiency

* Average patient stay remained at **5.71 days**, providing valuable insights for bed occupancy planning and resource allocation.

---

## 📌 DAX Measures Used

```DAX
Total Revenue =
SUM(Fact_Patient_Visit[Revenue])

Total Cost =
SUM(Fact_Patient_Visit[Cost])

Net Profit =
[Total Revenue] - [Total Cost]

Average Length of Stay =
AVERAGE(Fact_Patient_Visit[Length_of_Stay])

Total Patients =
DISTINCTCOUNT(Fact_Patient_Visit[Patient_ID])
```

---
## 🚀 Business Impact

* Improved visibility into hospital financial performance.
* Enabled data-driven capacity planning and resource allocation.
* Identified high-performing departments contributing most to profitability.
* Enhanced understanding of patient demographics and admission trends.
* Supported executive decision-making through interactive healthcare analytics.

---
