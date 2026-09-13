# Customer Shopping Behavior Analysis

An end-to-end data analytics project focused on understanding customer purchasing behavior, sales performance, product trends, and subscription patterns using Python, SQL, and Power BI.

## Project Overview

This project analyzes customer shopping data to identify patterns in purchasing behavior and generate business insights that can support customer segmentation, sales analysis, and decision-making.

The analysis covers:

- Customer demographics and purchasing behavior
- Product category performance
- Revenue and purchase trends
- Customer segmentation
- Subscription behavior
- Discount and promotional activity
- Repeat purchasing patterns
- Regional and seasonal trends

## Tools & Technologies

- Python
- Pandas
- NumPy
- SQL
- PostgreSQL
- Power BI
- DAX
- Jupyter Notebook
- Git & GitHub

## Dataset

The dataset contains **3,900 customer purchase records** with information including:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

## Analysis Workflow

### 1. Data Preparation

Used Python and Pandas to inspect, clean, transform, and prepare the dataset for analysis.

### 2. Exploratory Data Analysis

Analyzed customer demographics, purchasing patterns, product categories, revenue distribution, discounts, subscriptions, and repeat purchasing behavior.

### 3. SQL Analysis

Used PostgreSQL to answer business questions using:

- Aggregations
- GROUP BY
- CASE statements
- Subqueries
- Joins
- Window functions
- Filtering and sorting

### 4. Customer & Subscription Analysis

As an additional analysis, I compared subscribed and non-subscribed customers based on:

- Number of customers
- Total revenue
- Average purchase amount

This analysis was implemented in both Python and SQL to validate the results across tools.

### 5. Power BI Dashboard

Built an interactive dashboard to present important business KPIs and customer trends using:

- DAX
- KPIs
- Slicers
- Data modeling
- Interactive visualizations

## Key Findings

Some of the analysis highlights include:

- The dataset contains 3,900 customer records.
- 2,847 customers were non-subscribers, while 1,053 customers had an active subscription.
- Non-subscribed customers generated higher total revenue because they represented a larger share of the customer base.
- Average purchase value was approximately $59.87 for non-subscribers and $59.49 for subscribers.
- The analysis also examines product discounts, stock/purchasing patterns, customer segments, and repeat purchasing behavior.

## My Additional Analysis

To extend the core analysis, I added a dedicated subscription-status analysis.

The analysis compares:

`Subscription Status → Customers → Total Revenue → Average Purchase`

I implemented this analysis independently in both Python and SQL and compared the results.

This helped me practice:

- Pandas `groupby()`
- Aggregation
- SQL `GROUP BY`
- `COUNT()`
- `SUM()`
- `AVG()`
- Cross-checking results between Python and SQL

## Business Questions

The project explores questions such as:

1. Which product categories generate the most revenue?
2. What purchasing patterns can be observed across customer segments?
3. How do subscribed and non-subscribed customers differ?
4. How does discount usage relate to purchasing behavior?
5. Which customers demonstrate repeat purchasing behavior?
6. How does customer age relate to revenue contribution?
7. Which products and categories show notable purchasing trends?

## Project Structure

```text
customer-shopping-behavior-analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── customer_shopping_behavior.csv
└── README.md
