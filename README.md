# 📊 Business Insights 360 — Power BI Project

## 📌 Project Overview

**Business Insights 360** is an end-to-end Power BI report built for **AtliQ Hardware** a fast-growing consumer electronics company that sells PCs, peripherals, and networking products across global markets through retailers, direct channels, and distributors.

This project was built as part of the **Codebasics Data Analytics Bootcamp** and represents my first complete, industry-level Power BI project.

---

## 🏢 Business Problem

AtliQ Hardware was heavily reliant on **Excel files** for data analytics and business reporting. This made it difficult to generate quick, reliable insights leading to a **major financial loss in the Latin America (LATAM) market**.

The company needed a centralized, interactive analytics platform to empower stakeholders across Finance, Sales, Marketing, Supply Chain, and Executive functions to make **faster, data-driven decisions**.

---

## 💡 Solution

A multi-view Power BI report integrating data from **SQL databases** and **Excel files**, designed to provide department-wise insights through **6 interactive dashboards** all accessible from a single Home View.

---

## 🗄️ Data Sources

| Source | Details |
|--------|---------|
| SQL Database (GDB041) | Sales & Transactions Data |
| SQL Database (GDB056) | Product & Customer Data |
| Excel — Market Share | Competitor market share data |
| Excel — Operational Expenses | Cost data by region |
| Excel — Sales Targets | Target benchmarks |

---

## ⚙️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development |
| Power Query | Data cleaning & transformation |
| DAX | KPI calculations & measures |
| SQL | Data extraction |
| Data Modeling | Star Schema design |

---

## 📊 Dashboard Overview

### 🏠 Home View
Navigation hub connecting all report pages. Provides a quick summary of report refresh date and data availability.

### 💰 Finance View
Displays a complete **Profit & Loss Statement** filterable by customer, product, region, or any time period. Key KPIs: Net Sales, GM%, Net Profit%.

### 🤝 Sales View
Analyzes **customer performance** across Net Sales, Gross Margin, and GM% with a profitability/growth matrix and unit economics breakdown.

### 📣 Marketing View
Tracks **product-level performance** across Net Sales, GM%, and Net Profit% with a segment-wise profitability matrix and regional breakdown.

### 🚚 Supply Chain View
Monitors **Forecast Accuracy, Net Error, and ABS Error** by customer and product segment to identify inventory risks (Excess Inventory / Out of Stock).

### 👔 Executive View
A **top-level consolidated dashboard** for leadership — combining revenue, market share, GM%, Net Profit%, and Forecast Accuracy in one view with PC market share trend vs competitors.

---

## 📈 Key Business Insights

1. **Revenue Growth with Profitability Crisis** — AtliQ achieved $19.37bn in Net Sales (+61.45% vs Target), yet Net Profit Margin stands at -20.71%
2. **Operational Expenses Outpacing Revenue** — OpEx grew 71.51% vs Net Sales growth of 61.45%, causing margin compression
3. **Revenue Leakage via Discounts** — Only 49.85% of Gross Sales is retained as Net Sales after pre & post-invoice deductions
4. **GM% Below Benchmark** — Gross Margin at 36.41% is 2.17% below the target benchmark
5. **Customer Concentration Risk** — Amazon drives $2.42bn in Net Sales but shows -1.81% decline in GM% due to heavy promotional allowances

---

## 🙏 Acknowledgements

A heartfelt thank you to **Dhaval Patel** sir and **Hemanand Vadivel** sir at [Codebasics](https://codebasics.io/) for designing such a practical, industry-relevant curriculum that bridges the gap between learning and real-world application.

