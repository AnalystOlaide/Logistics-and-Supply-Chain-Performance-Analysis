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
  
## Data Analysis Process

* Data cleaning using Power Query
* Data modeling using Power Pivot
* KPI development and metric calculations using Pivot Tables
* Dashboard design using wireframes and structured layout
* Business insight extraction through trend and pattern analysis
  
## Executive Summary

The business generated $57,152 from 2,000 orders, moving over 101,292 units. Revenue peaked in April, while unit volume was highest in May, showing a disconnect driven by pricing or product mix. June’s high revenue despite low volume suggests a shift to premium or higher-margin items.

Medical Devices and Photography Equipment drove the highest revenue at $18,361 and $16,538, respectively, while Health Supplies and Banking Equipment underperformed.

Port Harcourt emerged as the most efficient warehouse, leading in both delivery and order transit rates. Abuja showed the slowest fulfillment, with the highest share of pending orders. Lagos handled the most orders, indicating smaller, frequent shipments.

FinServe Devices had the slowest supplier delivery time at 4.7 days, while GlobalTech Ltd. was the fastest at 4.3 days.

The business appears to be optimizing fulfillment by leveraging Port Harcourt’s efficiency and shifting toward high-margin products, enhancing revenue per shipment.



<img width="901" height="483" alt="image" src="https://github.com/user-attachments/assets/9c142b54-111f-42ee-8c3c-6f0f600fa91d" />

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

Optimize Abuja’s Warehouse to Reduce Pending Orders
Investigate key causes of high pending order rates—such as staff capacity, inventory lag, and dispatch timelines—and implement targeted improvements. Set a measurable goal to reduce pending orders by 15% within the next month.

Leverage Port Harcourt’s Operational Strategies Across All Warehouses
Study Port Harcourt’s workflow, staffing structure, and order fulfillment process, which led to the highest delivery and lowest pending rates. Use these insights to create a standard operations playbook and implement it in Abuja and Lagos to boost efficiency.

Analyze Product Mix for April–June Revenue Peaks
Identify which SKUs and campaigns drove the revenue spike in April, June, and February. Use this analysis to replicate demand-generation strategies and refine inventory and marketing plans for upcoming quarters.

Prioritize and Promote High-Performing Product Categories
Scale sales and marketing efforts around Medical Devices and Photography Equipment through promotions, bulk deals, or bundled offers. Ensure stock availability and sales alignment to increase their share of overall revenue.

Resolve FinServe Devices’ Delivery Delays
Audit FinServe Devices’ supply chain to pinpoint delivery bottlenecks. Consider process re-engineering, new SLAs, or replacing with more reliable vendors to reduce lead times from 4.7 days to below 4.3 days.

Enhance Lagos Warehouse for High-Frequency, Small-Volume Orders
Introduce faster picking systems or light automation to handle its high order volume (685+ orders). Improve order cycle times while maintaining accuracy and reduce operational fatigue caused by frequent dispatching.

## Tools and Skills Applied

* Data Cleaning using Power Query
* Data Modeling using Power Pivot
* KPI and Metrics Setup using Pivot Tables
* Dashboard Wireframing and Layout Design
* Business Insight Extraction and Interpretation


