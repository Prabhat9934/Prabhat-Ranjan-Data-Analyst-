# 🏏 IPL Tournament Analytics Dashboard

## 📌 Project Overview

This project provides a comprehensive analytics solution for IPL tournament data using SQL and Power BI. The dashboard helps sports franchise management analyze team performance, match outcomes, player statistics, and historical trends to support strategic decision-making.

---

## 🎯 Business Problem

Sports franchise management needed a centralized analytics platform to evaluate match variables, player performance, and historical tournament trends. The goal was to identify key factors influencing match outcomes and provide actionable insights for tournament strategy.

---

## 🛠️ Tools & Technologies

* SQL Server
* Power BI
* Advanced DAX
* Data Modeling
* Power Query
* Theme Customization

---

## 📊 Key Performance Indicators (KPIs)

| KPI                 | Value   |
| ------------------- | ------- |
| Total Runs          | 23,000+ |
| Total Sixes         | 1,062   |
| Total Fours         | 2,020   |
| Overall Strike Rate | 128.70  |
| Total Wickets       | 848     |

---

## 📈 Dashboard Features

### Executive Summary

* Overall tournament statistics
* Match outcome analysis
* Team performance overview

### Team Analysis

* Franchise-wise performance comparison
* Season-wise win trends
* Team ranking analysis

### Batting Analysis

* Total runs scored
* Strike rate analysis
* Boundary distribution (4s & 6s)

### Bowling Analysis

* Total wickets taken
* Bowling performance trends
* Match impact analysis

### Interactive Filters

* Season
* Team
* Venue
* Match Result
* Toss Decision

---

## 🔍 Key Insights

### 1. Toss Advantage

Teams choosing to field first after winning the toss achieved an impressive **80.56% win rate**, accounting for **29 match victories**.

### 2. Match Outcome Distribution

Historical tournament analysis revealed a balanced outcome pattern:

* 50% of matches won by runs
* 50% of matches won by wickets

### 3. Franchise Performance

* Gujarat Titans recorded the highest number of wins (**12**).
* Rajasthan Royals closely followed among top-performing franchises.

### 4. Historical Trends

* Consistent relationship observed between toss decisions and match outcomes.
* Strong batting performances contributed significantly to winning percentages.

---

## 🏗️ Data Model

The project follows a star schema approach:

* Fact_Matches
* Fact_Deliveries
* Dim_Team
* Dim_Player
* Dim_Venue
* Dim_Date

This structure enables efficient reporting and advanced DAX calculations.

---

## 📌 DAX Measures Used

Examples of key measures:

```DAX
Total Runs = SUM(Deliveries[TotalRuns])

Total Wickets = SUM(Deliveries[IsWicket])

Overall Strike Rate =
DIVIDE(
    SUM(Deliveries[BatsmanRuns]) * 100,
    COUNTROWS(Deliveries)
)
```

---

## 📸 Dashboard Preview

Add screenshots of:

* Executive Dashboard
* Team Analysis Dashboard
* Batting Analysis Dashboard
* Bowling Analysis Dashboard

---

## 🚀 Business Impact

* Enabled data-driven decision-making for franchise management.
* Identified critical factors affecting match outcomes.
* Improved understanding of team and player performance trends.
* Delivered actionable insights through interactive visualizations.

---

#
