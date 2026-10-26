# E-Commerce Data Analysis

## Project Overview

This project analyzes e-commerce sales data to understand revenue performance, customer behavior, product performance, sales trends, payment methods, and regional performance.

The project uses SQL and Python to transform raw data into meaningful business insights and recommendations.

## Business Objective

The main objectives of this project are:

* Analyze overall sales performance
* Identify the highest-performing product categories
* Analyze monthly revenue trends
* Identify top-performing products
* Analyze revenue by city
* Understand customer purchasing behavior
* Analyze payment methods
* Calculate cancellation and customer retention rates
* Provide actionable business recommendations

## Dataset

The project contains three main datasets:

* `customers.csv` — Customer information
* `products.csv` — Product information
* `orders.csv` — Order transaction information

### Dataset Size

* Customers: 2,000
* Products: 100
* Orders: 10,000

## Tools & Technologies

* MySQL
* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Analysis Process

The project was completed in the following stages:

1. Data loading
2. Data validation and cleaning
3. SQL analysis
4. Python/Pandas analysis
5. Data visualization
6. Business insights
7. Business recommendations

## Key Performance Indicators

| KPI                  |         Result |
| -------------------- | -------------: |
| Total Revenue        | ₹72,067,144.37 |
| Total Orders         |         10,000 |
| Total Customers      |          2,000 |
| Total Units Sold     |         19,268 |
| Average Order Value  |      ₹7,206.71 |
| Cancellation Rate    |          8.07% |
| Repeat-Customer Rate |          96.1% |

## Key Business Insights

### 1. Revenue by Category

Fashion was the highest-performing category, generating approximately ₹20.50M and contributing 28.45% of total revenue.

Fashion and Beauty together contributed approximately 54.29% of total revenue.

### 2. Monthly Revenue

October was the strongest month, generating approximately ₹6.90M in revenue.

September recorded the lowest monthly revenue at approximately ₹5.39M.

### 3. Top Product

Product_077 was the highest-revenue product, generating approximately ₹5.73M and contributing about 7.96% of total revenue.

The top 10 products collectively generated approximately ₹27.22M.

### 4. Revenue by City

Ahmedabad was the highest-revenue city, generating approximately ₹8.54M.

Pune and Kolkata were the next two highest-performing cities.

### 5. Payment Methods

UPI was the dominant payment method, accounting for 38.25% of revenue.

Credit Cards contributed 24.48%.

Together, UPI and Credit Cards represented 62.73% of revenue.

### 6. Customer Retention

The calculated repeat-customer rate was 96.1%, indicating strong repeat purchasing behavior under the project's retention definition.

### 7. Cancellation Rate

The cancellation rate was 8.07%, meaning approximately 8 out of every 100 orders were cancelled.

## Business Recommendations

### Focus on Fashion and Beauty

Increase marketing and promotional activity around Fashion and Beauty because these categories generate more than half of total revenue.

### Learn from October

Investigate the factors behind October's strong performance and consider applying successful strategies to other months.

### Protect Top Products

Maintain sufficient inventory for high-performing products such as Product_077 and use them for promotions and cross-selling.

### Prioritize High-Performing Cities

Focus regional marketing efforts on Ahmedabad, Pune, and Kolkata while identifying strategies that can improve performance in other markets.

### Optimize Digital Payments

Maintain a fast and reliable UPI and card checkout experience because these payment methods account for a large share of revenue.

### Reduce Cancellations

Investigate the main causes of the 8.07% cancellation rate, including delivery issues, payment failures, product availability, and customer cancellations.

### Maintain Customer Retention

Continue loyalty programs, personalized offers, and product recommendations to maintain strong repeat purchasing behavior.

## Project Structure

Ecommerce-Data-Analysis/
│
├── data/
│   ├── customers.csv
│   ├── products.csv
│   └── orders.csv
│
├── sql/
│   └── ecommerce_analysis.sql
│
├── python/
│   └── ecommerce_analysis.ipynb
│
└── README.md

## Conclusion

This analysis provides a detailed view of e-commerce business performance using SQL and Python.

The analysis identified key revenue drivers, high-performing products and cities, monthly sales patterns, customer behavior, payment preferences, and areas for improvement.

The results can help the business make data-driven decisions related to marketing, inventory, customer retention, regional strategy, and order management.
