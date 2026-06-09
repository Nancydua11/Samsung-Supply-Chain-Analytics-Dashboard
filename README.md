# 📊 Samsung Supply Chain & Logistics Dashboard

## Overview

The Samsung Supply Chain & Logistics Dashboard is an end-to-end Business Intelligence solution developed in Power BI to monitor and analyze the complete supply chain lifecycle, including procurement, production, inventory management, shipment tracking, and sales performance.

The dashboard provides actionable insights through interactive visualizations, KPI monitoring, trend analysis, and operational performance tracking, enabling better business decision-making across the supply chain network.

---

## Project Objectives

* Monitor overall supply chain performance.
* Analyze procurement and supplier efficiency.
* Track production output and quality metrics.
* Optimize inventory levels and stock availability.
* Monitor shipment and logistics operations.
* Evaluate sales performance, profitability, and revenue growth.
* Provide executive-level insights through a centralized dashboard.

---

## Tools & Technologies

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Power Query
* Data Modeling (Star Schema)
* GitHub Image Hosting
* Supply Chain Analytics

---

## Dashboard Pages

### 🏠 Home Page

The landing page provides navigation to all dashboard modules and includes a Samsung-themed interactive design.

### 👨‍💼 Executive Dashboard

Executive-level overview of supply chain performance.

**Key KPIs**

* Total Revenue
* Total Profit
* Profit Margin %
* Cost Ratio %
* Perfect Order Rate %
* Cash Cycle Days
* Current Stock Level
* Total Order Quantity

**Insights**

* Supplier Performance
* Inventory Overview
* Shipment Analysis
* Customer Revenue Analysis

---

### 🚚 Supplier Dashboard

Analyzes procurement operations and supplier performance.

**Key KPIs**

* Procurement Cost
* Total Order Quantity
* Average Unit Cost
* Average Lead Time
* Delivery Performance
* Delivery Score
* On-Time Delivery %

**Insights**

* Procurement Cost Growth (MoM)
* Shipment Distribution
* Shipment Cost Analysis
* Discount Analysis
* Supplier Detail Table

---

### 🏭 Production Dashboard

Monitors manufacturing efficiency and product quality.

**Key KPIs**

* Total Units Produced
* Total Defective Units
* Average Defect Rate %
* Quality Yield %
* Production Efficiency %

**Insights**

* Production Growth MoM
* Defect Rate Trends
* Production by Category
* Facility Performance Analysis

---

### 📦 Inventory Dashboard

Provides inventory management and stock monitoring insights.

**Key KPIs**

* Inventory Turnover
* Days of Inventory
* Stock Coverage Days
* Inventory Accuracy %
* Inventory Value

**Insights**

* Inventory Value by Product
* Current Stock Level
* Overstock vs Understock Analysis
* Safety Stock Monitoring
* Reorder Point Analysis

---

### 🚛 Shipment Dashboard

Tracks logistics operations and delivery performance.

**Key KPIs**

* Total Shipments
* On-Time Delivery %
* Delayed Shipments
* In Transit Shipments
* Total Shipping Cost
* Quantity Shipped

**Insights**

* Delivered vs Delayed Shipments
* In Transit Shipment Trends
* Carrier Performance
* Shipment Cost Analysis
* Customer Shipment Analysis

---

### 💰 Sales Dashboard

Analyzes sales performance, revenue generation, and profitability.

**Key KPIs**

* Total Revenue
* Total Profit
* Profit Margin %
* Total Orders
* Total Quantity Sold
* Revenue Growth YoY

**Insights**

* Revenue Growth by Customer
* Product Profitability Analysis
* Revenue vs Quantity Sold by Category
* Monthly Revenue & Profit Trends
* Customer Logo-Based Revenue Tracking

---

## Key Features

### Dynamic Product Gallery

Implemented using image URLs and slicer interactions to create a dynamic Samsung product showcase.

### Customer Logo Integration

Customer logos are hosted on GitHub and displayed dynamically within Power BI using Image URL categorization.

### Advanced DAX Measures

Custom measures developed for:

* Revenue Growth YoY
* Profit Margin %
* Inventory Turnover
* Days of Inventory
* Procurement Cost Growth MoM
* Quality Yield %
* Production Efficiency %
* Inventory Accuracy %
* On-Time Delivery %
* Stock Coverage Days

---

## Data Model

### Fact Tables

* fact_sales
* fact_procurement
* fact_production
* fact_inventory
* fact_shipment

### Dimension Tables

* dim_date
* dim_customer
* dim_product
* dim_supplier
* dim_facility

### Modeling Approach

* Star Schema Design
* One-to-Many Relationships
* Centralized Date Dimension

---

## Business Value

This dashboard helps organizations:

* Improve supply chain visibility.
* Reduce inventory costs.
* Optimize procurement operations.
* Enhance shipment tracking.
* Monitor supplier performance.
* Improve production quality.
* Increase profitability through data-driven decisions.

---

## Repository Structure

Samsung-Supply-Chain-Dashboard/

├── Dashboard/

│   └── Samsung_Supply_Chain_Dashboard.pbix

├── Dashboard Screenshots/

│   ├── Home.png

│   ├── Executive.png

│   ├── Supplier.png

│   ├── Production.png

│   ├── Inventory.png

│   ├── Shipment.png

│   └── Sales.png

├── Assets/

│   ├── Customer Logos

│   └── Product Images

├── DAX Measures/

│   └── Measures.txt

└── README.md

---

## Author

**Nancy Dua**

B.Tech Computer Science Engineering

Aspiring Data Analyst | Power BI Developer | SQL | Excel

---

⭐ If you found this project helpful, consider giving it a Star on GitHub.
