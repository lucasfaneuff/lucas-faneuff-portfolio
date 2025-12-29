# Budget Variance Analysis
## 📌 Project Overview
This project analyzes actual vs budget performance of a coffee company across products and time to identify areas of underperformance, drivers of profitability and margin performance. The goal of the project is to provide a stakeholder ready dashboard that monitors performance and data driven decision making.

The final deliverable is a one page excel dashboard designed for executuve review, trend comparisons, product level variance and margin analysis.

<img width="1683" height="621" alt="Screenshot 2025-12-29 124212" src="https://github.com/user-attachments/assets/b4407adb-1fdb-4bce-937c-c957a99d221e" />

## 📊 Business Problem
The company lacks an organizaed, centralized view of financial budget perfoamcne across products and time making it hard for stakeholder to quickly identify trends, drivers and variances. This results in possible misunderstanding of product performance, extra time spent on financial reviews and decision making, and variances in budget vs actual not being recognized or actionable.

## ️🗂️ Dataset
Type: Simulated / anonymized business data 

Time Period: 2010–2011 

## 📐 KPIs
Total Revenue: Sum of actual sales

Total Profit: Revenue - Expenses

Profit Variance: Actual Profit - Budget Profit

Profit Margin %: Profit / Revenue

Expense Ratio %: Expenses / Revenue

## 🧼 Data Cleaning & Preparation
- Standardized data types
- Created calculated fields (transaction key, variances, gross margin %, profit margin %, expense ratio %)
- Organized data into star schema with fact and dimension tables to support scalability

## 📊 Methodology
1. Built a structured data model using power pivot
2. Created KPI and supporting measures to ensure consistency
3. Built pivot tables for product level and time series analysis
4. Developed a stakeholder ready dashboard with KPI cards, charts (line and bar) and interactive slicers (product, product type and month) for intuitive exploration

## 🔍 Key Insights
- Profit variance is highly concentrated (tea is the only product type with a positive profit variance of $3127)
- A negative profit variance is driven by small margins (margin compression) rather than revenue declines
- High margin products no not guarentee high profit due to volume or expenses issues (Columbian and decaf espresso have above average gross margins but below average profit variance)
- Profit performance is strongly associated with top performing products (Earl Grey and Darjeeling provide $46722 in total profit and 6262 in profit variance)

## ️ ⚠️ Assumptions & Limitations
