#  Adventure Works Sales Dashboard | Power BI

An end-to-end interactive Power BI dashboard built on the **Adventure Works Cycles** dataset, designed to help business leaders monitor sales performance, track regional trends, and analyze customer behavior — all in one place.

##  Project Overview

This dashboard transforms raw sales data into actionable business insights through 4 interconnected report pages, complete with KPI tracking, geographic visualization, product drill-through, and customer segmentation.

##  Dashboard Pages

### 1️⃣ Executive Summary
- KPI cards: **Total Revenue ($18.51M)**, **Total Profit ($7.86M)**, **Total Orders (53K)**, **Return Rate (2.14%)**
- Monthly trend line comparing Revenue vs Cost vs Profit
- Orders by Category and Continent breakdown
- Top 10 products by order volume and return rate
- Interactive slicers: Year, Month, Continent

### 2️⃣ Geographic Analysis (World Map)
- Bubble map visualization showing order volume by country
- Region-based filtering (Europe, North America, Pacific)
- Quick visual comparison of global sales distribution

### 3️⃣ Product Details (Drill-Through Page)
- Gauge charts for Monthly Revenue, Orders, and Returns vs targets
- Weekly revenue trend with forecast line
- Weekly returns tracking by order
- Accessible via drill-through from any product in the Executive Summary

### 4️⃣ Customer Details
- Customer-level order and revenue breakdown
- Demographic analysis: Gender, Income Level, Occupation, Age
- Orders and Revenue trend by month
- Top Customer, Top Orders, and Top Revenue callouts

##  Tools & Techniques Used
- **Power BI Desktop** — data modeling, visualization, and report design
- **DAX** — calculated columns, measures, time intelligence (YTD, MTD, SAMEPERIODLASTYEAR)
- **Data Modeling** — star schema with fact and dimension tables (Sales Data, Customers_Lookup, Products_Lookup, Territories_Lookup, Calendar_Lookup)
- **Interactivity** — slicers, cross-filtering, drill-through pages, bookmarks
- **Forecasting** — trend lines and forecast analytics on revenue data

##  Key Insights
- Identified top-performing and highest-return products to guide inventory decisions
- Highlighted regional sales concentration (United States and United Kingdom as top markets)
- Built customer segmentation by income, occupation, and age to support targeted marketing

##  Files in This Repository
- `Adventure_Works_Dashboard.pbix` — Power BI project file
- `/screenshots` — Preview images of all dashboard pages
- `README.md` — Project documentation

##  Connect
Built by **Hadia Ahad** | Data Analyst
- LinkedIn: [linkedin.com/in/hadi12](https://linkedin.com/in/hadi12)
- Portfolio: [GitHub Profile](https://github.com/Hadia3112)

---
⭐ If you found this project useful, feel free to star this repository!
