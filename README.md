# Customer_Behavior_Analysis
Customer Shopping Behavior Analysis using Python, SQL Server &amp; Power BI — Data cleaning, SQL analysis, customer insights, and interactive dashboard creation.
# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior to identify purchasing patterns, customer segments, product trends, and factors influencing customer spending.

The project follows a complete end-to-end data analytics workflow, starting with data loading and cleaning in Python, followed by exploratory data analysis, SQL analysis using SQL Server, and visualization through an interactive Power BI dashboard.

The analysis aims to answer key business questions and provide actionable insights that can help improve customer engagement, sales, marketing strategies, and product decisions.

---

## Business Problem

A retail company wants to better understand its customers' shopping behavior and purchasing patterns.

The key objectives are to:

- Understand customer purchasing behavior
- Identify high-performing product categories and products
- Analyze customer spending patterns
- Evaluate the impact of discounts and promotions
- Compare subscribed and non-subscribed customers
- Analyze customer segments and repeat purchases
- Identify trends based on age, gender, season, and payment methods
- Provide data-driven recommendations for marketing and business strategy

---

## Dataset

The dataset contains customer shopping behavior information, including customer demographics, purchases, product details, discounts, reviews, subscriptions, and payment preferences.

### Key Columns

- `customer_id` – Unique customer identifier
- `age` – Customer age
- `gender` – Customer gender
- `item_purchased` – Product purchased
- `category` – Product category
- `purchase_amount` – Purchase amount
- `location` – Customer location
- `size` – Product size
- `color` – Product color
- `season` – Purchase season
- `review_rating` – Product review rating
- `subscription_status` – Customer subscription status
- `shipping_type` – Shipping method
- `discount_applied` – Whether a discount was applied
- `previous_purchases` – Number of previous purchases
- `payment_method` – Payment method used
- `frequency_of_purchases` – Purchase frequency

---

## Tools & Technologies

### Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### SQL
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)

### Visualization
- Microsoft Power BI

### Reporting & Presentation
- Data Analytics Report
- Gamma for presentation creation

### Version Control
- Git
- GitHub

---

## Project Workflow

The project was completed in the following stages:

### 1. Data Loading

The dataset was loaded into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")
