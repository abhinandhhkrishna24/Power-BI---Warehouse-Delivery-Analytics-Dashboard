# Warehouse Delivery Analytics Dashboard

A multi-page Power BI dashboard analyzing warehouse order and delivery operations — covering revenue performance, delivery efficiency, driver productivity, and order fulfillment trends across multiple cities.

![Home](screenshot/home.png)

---

## 📌 Overview

This project simulates an end-to-end warehouse logistics analytics solution, built to track order volume, delivery performance, refund/cancellation patterns, and driver workload across a multi-year dataset (16K+ orders, $39.83M in revenue). The dashboard is designed for stakeholders at different levels — from executive-level KPIs to granular order-level detail.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Power Query** | Data extraction, cleaning, and transformation |
| **DAX** | Calculated columns, measures, and calculated tables (including cross-table `SUMMARIZE` logic) |
| **Power BI Desktop** | Data modeling, visualization, and report design |

---

## 📊 Dashboard Pages

### 1. Overview
Revenue, total orders, unique customers, delivery failure rate, average delivery time, monthly order trends, revenue by city, and top-performing shops.

![Overview](screenshot/pg1.png)

### 2. Performance
Refund rate trends, ASAP order percentage, average shipping/delivery time vs SLA targets, order fulfillment funnel, and order volume vs delivery time correlation.

![Performance](screenshot/pg2.png)

### 3. Drivers & Delivery
Active driver count, orders per driver, driver workload distribution, and individual driver performance and delivery time benchmarking.

![Drivers & Delivery](screenshot/pg3.png)

### 4. Order & Delivery Report
Full transactional detail table with customer, shop, area, order value, discount, refund, delivery fee, and delivery status.

![Order & Delivery Report](screenshot/pg4.png)

---

## 🔑 Key Insights

- Identified delivery failure rate trends and SLA variance against a 45-minute target
- Built a driver performance scorecard to flag workload imbalance and delivery time outliers
- Analyzed refund rate seasonality by month and hour to surface operational patterns
- Designed cross-filterable Year/Month slicers for dynamic time-based analysis

---

## 💡 Skills Demonstrated

- Data cleaning and transformation using **Power Query**
- **DAX** calculated tables, measures, and cross-table `SUMMARIZE` logic
- Data modeling and relationships within **Power BI**
- Dashboard UX and multi-page navigation design
- Business-focused KPI storytelling for executive and operational audiences

---

## 👤 Author

**Abhinandh**
Credit Analyst | Aspiring Data Analyst | Power BI & SQL Enthusiast
