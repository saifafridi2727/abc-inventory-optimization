# ABC Inventory Optimization & Pareto Analysis

## 📌 Project Overview
Conducted a complete Supply Chain ABC (Pareto) inventory analysis on a retail dataset containing **3,791 SKUs** to classify products by revenue contribution and optimize inventory management.

## 🎯 Business Problem
Not all inventory is created equal. Managing all SKUs the same way wastes time and money. The 80/20 Pareto principle suggests that a small percentage of products generate the majority of revenue—identifying these "A" items is critical for supply chain efficiency.

## 🛠️ Tools Used
- **Google Sheets** (PivotTables, SUMIF, IF logic, Pareto Charting)

## 📊 Key Insights
- **21.5%** of products (Class A) generate **80%** of total revenue.
- **53%** of products (Class C) generate only **5%** of revenue.

## 💡 Recommended Strategy
Proposed a 3-tier inventory strategy:
- **A (Protect):** Daily reviews, weekly forecasts, never run out.
- **B (Manage):** Monthly reviews, standard batch orders.
- **C (Ignore Cheaply):** Quarterly reviews, bulk ordering to save costs.

## 📁 Files in this Repository
- `Dashboard_Screenshot.png` – Live KPI dashboard showing A/B/C classification.
- `Pareto_Chart.png` – Visual 80/20 curve showing revenue concentration.
- `ABC_Classification_Table.png` – Detailed breakdown of products by tier.
- `Recommendation_Report.pdf` – Full report with inventory strategy recommendations.
- `Sample_Data.csv` – Sample of the raw SKU data (first 100 rows).

## 🔗 Live Project
[View the live Google Sheet here](https://docs.google.com/spreadsheets/d/1NfMrxZqVr7xhngXmZXVmVjSDYSCnvGkH2hodnbT22nc/edit?usp=sharing)

## 🧠 What I Learned
- How to apply the Pareto Principle (80/20 rule) to real inventory data.
- How to build a dynamic classification system using `IF` logic and `SUMIF`.
- The importance of tiered inventory strategies for cost optimization.
