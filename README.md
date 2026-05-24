# BI-ERP Integration: Target Canada Inventory Management

**University of Newcastle · Business Analytics · 2024**  
`Power BI` `Power Query` `Excel` `OLAP` `ERP Analysis` `Business Intelligence` `Demand Forecasting` `Data Governance`

---

## 📌 Project Overview

This project analyses the inventory management failures that contributed to Target Canada's 2015 collapse — one of the most high-profile retail business failures in Canadian history — and designs a **BI-enhanced ERP improvement framework** to address the root causes.

Using business intelligence tools, data integration architecture, and machine learning concepts, the project demonstrates how better reporting, real-time visibility, and demand forecasting could have prevented critical supply chain breakdowns. The deliverable is a practical, stakeholder-ready framework for BI-driven inventory management improvement.

---

## 🎯 Business Problem

Target Canada's inventory management system suffered from three critical failures:

1. **Data accuracy issues** — ERP data was riddled with errors in product dimensions, quantities, and supplier lead times, causing systematic replenishment failures
2. **Visibility gaps** — no real-time tracking of stock levels, product movement, or delivery performance across distribution centres and stores
3. **Forecasting failures** — demand planning relied on assumptions from Target US operations rather than Canadian market data, leading to chronic overstock and stockout cycles

> **Result:** Shelves were simultaneously overstocked with wrong products and out of stock on high-demand items — destroying customer trust and driving the $2 billion loss that forced store closures.

---

## 📂 Repository Contents

| File | Description |
|---|---|
| `customers.csv` | Customer dataset used for analysis |
| `orders.csv` | Order transaction data |
| `products.csv` | Product inventory data |
| `Interactive Dashboard.pbix` | Power BI dashboard file — inventory tracking and KPI visualisation |
| `Enhancing Target Canada Inventory Management Through BI-ERP Integration Report` | Full project report with analysis, framework design, and recommendations |

---

## 🔧 Methodology

### 1. Current-State Analysis (AS-IS)
- Reviewed Target Canada's ERP system failures, inventory data quality issues, and supply chain reporting gaps
- Identified root causes of stockouts, overstock cycles, and decision-making delays using structured business analysis
- Mapped how data flows (and broke down) between ERP, POS systems, warehouse management, and management reporting

### 2. BI-Enhanced ERP Framework Design
Designed a four-component improvement framework:

**Component 1 — Data Integration & Centralisation**
- Integrate data from ERP, POS, and warehouse management systems into a **centralised data warehouse**
- Establish a single source of truth for inventory data across all departments
- Implement data validation and quality controls at the point of entry to prevent upstream errors

**Component 2 — Real-Time Inventory Visibility**
- Deploy Power BI dashboards connected to live ERP data feeds
- Monitor stock levels, product movement, and delivery performance in real time
- Automated alerts for stockout risk, overstock thresholds, and delivery exceptions

**Component 3 — Advanced Analytics & Demand Forecasting**
- Apply **OLAP cubes** for multidimensional inventory analysis (by product, region, season, supplier)
- Implement **machine learning demand forecasting** using historical Canadian sales data, regional trends, and seasonal patterns — replacing the flawed US-assumptions model
- Power Query transformations for automated data cleaning and refresh

**Component 4 — Decision Support & Management Reporting**
- Interactive Power BI dashboards for store managers, supply chain leads, and executives
- KPI tracking: inventory turnover, fill rate, days of supply, stockout frequency, supplier lead time accuracy
- Self-service analytics enabling managers to investigate issues without IT dependency

### 3. Power BI Dashboard
Built an interactive dashboard demonstrating:
- Inventory levels by product category and region
- Order fulfilment performance and delivery tracking
- Demand vs. supply trend analysis
- KPI summary for executive reporting

---

## 📊 Framework Outcomes

| Problem | Root Cause | BI Solution |
|---|---|---|
| Chronic stockouts | No real-time visibility | Live Power BI dashboards with automated alerts |
| Overstock accumulation | Poor demand forecasting | ML-based forecasting using local Canadian data |
| Data accuracy errors | No data validation at entry | Centralised data warehouse with validation controls |
| Delayed decisions | Siloed, manual reporting | Self-service analytics and automated KPI tracking |
| Supply chain blind spots | Disconnected systems | Integrated ERP-POS-warehouse data architecture |

> **Projected impact of BI framework:** Significant reduction in stockout and overstock frequency, faster identification of supply chain issues, and improved management decision-making speed — addressing the core failures that led to Target Canada's collapse.

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| BI & Dashboards | Power BI Desktop |
| Data Transformation | Power Query (M language) |
| Multidimensional Analysis | OLAP concepts |
| Data Analysis | Excel, DAX |
| Forecasting Concepts | Machine learning (regression, demand forecasting) |
| Data Architecture | Data warehouse design concepts |

---

## 📄 Full Report

A complete project report covering the business case, current-state analysis, BI-ERP framework design, dashboard specifications, risk assessment, and stakeholder recommendations is available in the repository:  
📎 [View Full Report](./Enhancing%20Target%20Canada%20Inventory%20Management%20Through%20BI%E2%80%93ERP%20Integration%20Report)

---

*Project completed as part of the Bachelor of Business Analytics at the University of Newcastle, 2024.*
