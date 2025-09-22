Introduction

This project is part of my internship work where I built an end-to-end Power BI dashboard for Electro Hub’s transactional data.

The goal was to transform raw sales, customer, product, and promotion data into actionable insights for business leaders.

Using Power Query, DAX, and Power BI visuals, I created a set of interactive reports covering sales performance, profitability, promotions, and customer/order-level analytics.

Business Problems

The business team wanted answers to questions such as:

Which products are contributing the most and least to sales, profit, and quantity sold?

How do sales, profit, and quantity compare between two different time periods?

What is the overall company performance in terms of sales, profit, orders, and discounts?

How are sales trends evolving over time, and what is the relationship between sales and profit?

Which cities contribute the most to sales?

What are the average discounts by promotion type, and are they effective?

How can we view order-level details (sales, discounts, profit) and filter them by customers, products, promotions, or dates?


Using Power BI, the following features were designed:

Data Cleaning & Transformation-

Removed duplicates, nulls, unnecessary columns.

Standardized headers and ensured correct data types.

Created calculated columns: DiscountValue, NetSales, Profit.


Data Modeling-

Built a Star Schema with one Fact Table (Sales) and multiple Dimensions (Customer, Product, Promotion, Date).

Created proper one-to-many relationships and ensured type consistency.


DAX Measures

Core metrics: Total Sales, Net Sales, Profit, Orders Count, Avg Discount %.

Two-period comparison measures using CALCULATE, ALL, USERELATIONSHIP.

SumDim measure to enable cross-filtering between slicers.


Dashboards & Requirements Fulfilled:

KPI Overview → Sales, Profit, Orders, Avg Discount.

Top & Bottom 5 Analysis → Products ranked by Sales, Profit, Quantity.

Period Comparison Page → Compare Sales, Profit, Quantity across two time ranges.

Trends & Profit Analysis → Line charts, Scatter plots, City map, Promotion discounts.

Order-level Table → Complete order details with slicer filters.

Interactive Slicers → Cross-filtering enabled for Date, Customer, Product, Promotion.


Business Value Delivered:

Identified top- and bottom-performing products to guide promotions and stock decisions.

Supported city-level targeting for sales campaigns and logistics planning.

Measured effectiveness of promotions/discounts on sales and profitability.

Provided transaction-level visibility for audits and customer service.

Enabled trend analysis for seasonal and festival-driven demand.


Tech & Skills Used:

Power BI Desktop – Data modeling, DAX, visualization.

Power Query Editor – Data cleaning and transformation.

Excel – Source data.

Data Analysis & Business Intelligence

Problem Solving & Insight Generation


Conclusion

This dashboard helps ElectroHub management to monitor performance in real-time, understand customer behavior, and optimize promotions and sales strategy.


This repository includes:

Project Report

Power BI Dashboard file

Screenshots of Dashboard

README with problem statement, solutions, and business insights
