# Logistics and Supply Chain Performance Analysis

## Project Overview

This project showcases a comprehensive Excel dashboard designed to deliver actionable insights into the supply chain and logistics performance of a business. Stakeholders include warehouse managers, supply chain executives, and logistics analysts who are responsible for ensuring seamless product flow, improving delivery efficiency, and maximizing profitability.

The goal is to empower decision-makers with a centralized, visual overview of core logistics operations such as revenue generation, warehouse performance, product movement, and supplier delivery efficiency. This enables real-time operational adjustments and long-term strategic planning.

## Problem Statement

Despite high order volume and consistent warehouse activity, the business faces challenges around delayed deliveries, revenue inconsistency, and uneven warehouse performance. To scale sustainably and ensure operational excellence, the organization must address the following questions:

* Which product categories drive the highest and lowest revenue?
* Which warehouse is most efficient in terms of delivery and order processing?
* How do revenue and order volumes trend across different months?
* Which suppliers contribute to delivery delays?
* How does the business optimize fulfillment while maximizing revenue per shipment?

## Data Structure

The dataset is organized across five primary tables:

* Customer
* Order
* Supplier
* Warehouse
* Product

## Executive Summary

The business generated a total revenue of 57,152 dollars across 2,000 orders, moving over 101,292 units. The monthly unit volume peaked in May, while the lowest volumes occurred in February and June. However, revenue does not follow volume exactly. It peaked in April, followed by June and February, while the lowest months were March, May, and January.

This pattern suggests changes in product mix or pricing strategies influencing monthly earnings. Notably, June's high revenue despite low volume signals a shift toward premium or higher-margin items.

<img width="903" height="482" alt="image" src="https://github.com/user-attachments/assets/54c12e02-c22f-4f1c-b12f-b4b8ea5bb7f4" />


## Insights Deep Dive

### Monthly Trends

* Units Volume: Highest in May, lowest in February and June
* Revenue: Highest in April, followed by June and February. Lowest in March, May, and January

### Warehouse Efficiency

Port Harcourt had the lowest percentage of pending orders at 30.68 percent and the highest for both in transit (33.83 percent) and delivered orders (35.49 percent), making it the most efficient warehouse.

Abuja had the highest pending orders at 34.66 percent and the lowest delivery rate at 34.00 percent, indicating delays.

Lagos maintained a balanced performance but showed room for improvement in delivery speed.

### Warehouse Order Volume

All warehouses moved approximately 34,000 or more units.

Lagos processed the most orders, with 685, suggesting it handles smaller, more frequent shipments.

### Product Category Revenue

* Medical Devices: 18,361 dollars
* Photography Equipment: 16,538 dollars
* Banking Equipment: 6,770 dollars
* Health Supplies: 6,001 dollars

Medical Devices and Photography Equipment generated the most revenue, while Health Supplies and Banking Equipment underperformed.

### Supplier Delivery Performance

* FinServe Devices: 4.7 days (slowest)
* GlobalTech Ltd.: 4.3 days (fastest)
* Other suppliers averaged around 4.5 days

Delivery times were mostly consistent, with FinServe Devices being the slowest.

## Recommendations

1. Optimize Abuja's warehouse to reduce pending orders.
2. Apply Port Harcourt's operational strategies across other warehouse locations.
3. Analyze product mix between April and June to maintain or improve revenue trends.
4. Focus on promoting high-performing product categories such as Medical Devices and Photography Equipment.
5. Address delivery delays with FinServe Devices by reviewing processes or adjusting supplier mix.
6. Refine Lagos warehouse operations to support efficient processing of high-frequency, small-volume

   &#x20;orders.

## Data Analysis Process

* Data cleaning using Power Query
* Data modeling using Power Pivot
* KPI development and metric calculations using Pivot Tables
* Dashboard design using wireframes and structured layout
* Business insight extraction through trend and pattern analysis

## Tools and Skills Applied

* Data Cleaning using Power Query
* Data Modeling using Power Pivot
* KPI and Metrics Setup using Pivot Tables
* Dashboard Wireframing and Layout Design
* Business Insight Extraction and Interpretation

## How to Use This Project

* Open the Excel file containing the dashboard
* Use slicers to filter by month, warehouse, or product
* Analyze KPIs and visual trends through Pivot Tables and charts
* Refer to this README for business context and key takeaways
