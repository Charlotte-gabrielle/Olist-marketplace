# Olist Marketplace Analytics Dashboard

## Project overview

Interactive Power BI dashboard analyzing e-commerce sales, customer behavior, and logistics performance using the Olist Marketplace dataset (2016-2018). The analysis relies on SQL for data preparation and querying, combined with Power BI for interactive data visualization and business insights.

The dashboard consists of three main analytical views:
- **Executive Summary:** Overall business health, total revenue (16.64M BRL), order volume (99K), AOV (BRL 167.37), revenue distribution by payment method, regional share, and top product categories.
- **Customer Analytics:** Customer segmentation, repeat buyer rate (10.42%), active customer rate (70.34%), revenue/AOV by segment, and customer satisfaction (review scores).
- **Logistics Performance:** Delivery times (avg 12.43 days), delayed orders rate (7.61%), freight cost impact, seller handover vs. transit times by region, and the correlation between delivery delays and customer review scores.

---
## Key Business Insights

- **Revenue & Market Concentration:** Total revenue reached BRL 16.64M (+312% YoY), driven by high order volume. Over 65% of sales are concentrated in the Southeast region, highlighting significant market dependency.
- **Customer Segmentation:** *Repeat Buyers* generate the highest Average Order Value (~BRL 490), making them the most profitable cohort. Meanwhile, *Budget Buyers* represent the largest customer base (38%), driving overall order volume.
- **Logistics & Customer Satisfaction:** Long delivery times (20+ days) and high delay rates are concentrated in the North and Northeast regions due to transit times rather than seller dispatch delays. Delivery delays over 4 days trigger a sharp drop in average customer satisfaction from 4.2 to below 2.0 stars.

---

## Technologies and skills

- **SQL** (Data querying, aggregation, and exploratory data analysis)
- **Power BI** (Data modeling, Star Schema, dynamic reporting)
- **DAX measures** (Time intelligence, YoY calculations, custom KPIs like Repeat Buyer Rate % and Avg Days vs Estimate)

---

## Attached files

- **Screenshots**
  - Executive Summary view
  - Customer Analytics view
  - Logistics Performance view
- **SQL Scripts** (Data modeling & preparation queries)
- **Olist_data.pbix** (Power BI dashboard file)

---

## Source

Brazilian E-Commerce Public Dataset by Olist. The dataset contains anonymized information on 100k orders placed between 2016 and 2018 across multiple marketplaces in Brazil, covering order status, price, payment, freight performance, customer locations, product attributes, and customer review scores.
