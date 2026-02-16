[Diwali_Sales_README.md](https://github.com/user-attachments/files/25335447/Diwali_Sales_README.md)
# Festive Revenue Optimization -- Diwali Sales Analysis

## Project Overview

This project analyzes festive season sales performance using PostgreSQL
and Power BI. The objective was to identify revenue drivers, customer
segmentation patterns, and regional performance gaps to support
data-driven strategic decisions.

------------------------------------------------------------------------

## Business Problem

A nationwide retail company observed uneven revenue growth during its
Diwali campaign despite high order volumes.

Key challenges: - Revenue concentrated in limited states - Uniform
marketing allocation without segment targeting - Inventory mismatch
across categories - Underperformance of certain high-margin products

Management required analytical insights to optimize next festive season
strategy.

------------------------------------------------------------------------

## Objectives

-   Identify high-value customer segments
-   Evaluate state-wise revenue contribution
-   Analyze product category performance
-   Provide actionable recommendations to increase revenue by 15%

------------------------------------------------------------------------

## Database & Technology Stack

-   PostgreSQL (Database & SQL Analysis)
-   Power BI (Dashboard & Visualization)
-   DAX (KPI Calculations)
-   Excel (Data Cleaning & Encoding Handling)

------------------------------------------------------------------------

## Database Schema

CREATE TABLE sales ( user_id INT, cust_name TEXT, product_id TEXT,
gender TEXT, age_group TEXT, age INT, marital_status INT, state TEXT,
zone TEXT, occupation TEXT, product_category TEXT, orders INT, amount
NUMERIC );

------------------------------------------------------------------------

## SQL Analysis Performed

-   Total Revenue & Orders Calculation
-   Revenue by Gender & Age Group
-   State-wise Revenue Ranking
-   Product Category Contribution Analysis
-   Customer Segmentation
-   Revenue Concentration Risk Analysis

Advanced SQL Techniques: - GROUP BY Aggregation - Window Functions
(RANK) - Revenue Contribution Percentage - Segmentation Queries

------------------------------------------------------------------------

## Power BI Dashboard Features

Executive KPIs: - Total Revenue - Total Orders - Average Order Value

Customer Insights: - Revenue by Gender - Revenue by Age Group - Revenue
by Occupation

Geographic Analysis: - State-wise Revenue Distribution - Zone
Performance Comparison

Product Insights: - Top Performing Categories - Category Revenue
Breakdown

------------------------------------------------------------------------

## Key Insights

-   Revenue heavily concentrated in top-performing states
-   Age group 26--35 showed highest purchasing behavior
-   Essential festive categories generated majority revenue
-   Opportunity exists for premium product upselling
-   Targeted marketing can improve ROI

------------------------------------------------------------------------

## Strategic Recommendations

1.  Reallocate marketing budget toward high-performing regions
2.  Implement demographic-based campaign targeting
3.  Optimize inventory allocation using demand trends
4.  Introduce bundled premium offerings
5.  Improve forecasting for festive season demand

------------------------------------------------------------------------

## Expected Impact

-   10--15% projected revenue increase
-   Improved marketing efficiency
-   Reduced inventory mismatch
-   Better geographic diversification

------------------------------------------------------------------------

## Interview Explanation

"I stored the festive sales dataset in PostgreSQL, performed
segmentation and revenue analysis using advanced SQL queries, and built
an interactive Power BI dashboard to provide strategic recommendations
for festive campaign optimization."

------------------------------------------------------------------------

## Author

Rohit Singh\
Aspiring Data Analyst \| SQL \| Power BI \| Business Analytics
