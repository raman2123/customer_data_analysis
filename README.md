# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using a retail dataset containing **3,900 customer transactions**. The objective is to uncover purchasing patterns, customer segments, revenue trends, and subscription behavior through Python, SQL, PostgreSQL, and Power BI.

## Dataset

The dataset contains:

- 3,900 customer transactions
- 18 columns
- Average purchase amount: **$59.76**
- Average review rating: **3.75**
- Customer demographics
- Purchase information
- Shopping behavior
- Shipping preferences
- Subscription status

### Features

- Age
- Gender
- Location
- Product Category
- Purchase Amount
- Season
- Size
- Shipping Type
- Review Rating
- Discount Applied
- Subscription Status
- Payment Method
- Purchase Frequency

---

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas

### 2. Data Cleaning
- Handled missing values
- Imputed missing review ratings using category median
- Standardized column names (snake_case)
- Removed redundant columns

### 3. Feature Engineering
- Created Age Groups
- Prepared data for SQL analysis

### 4. Database
- Loaded cleaned dataset into PostgreSQL

### 5. Analysis
Performed exploratory data analysis using SQL and Python.

### 6. Visualization
Built an interactive Power BI dashboard.

---

## Tech Stack

- Python
- Pandas
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

---

## Key Insights

### Revenue by Gender

- Male customers generated approximately **2.1×** more revenue than female customers.

---

### Customer Segmentation

- Loyal Customers: **3,116**
- Returning Customers: **701**
- New Customers: **83**

---

### Product Ratings

Top Rated Products:

1. Gloves
2. Sandals
3. Boots
4. Hat
5. Skirt

---

### Highest Discount Usage

- Hat
- Sneakers
- Coat
- Sweater
- Pants

---

### Revenue by Age Group

Highest spending age group:

- Young Adults

---

### Shipping Analysis

- Express shipping customers spend approximately **$2 more** per purchase than standard shipping customers.

---

### Subscription Analysis

- Subscribers: **27%**
- Non-Subscribers: **73%**

Subscribers demonstrate stronger customer loyalty, although average spending per purchase remains similar.

---

## Recommendations

- Increase subscription adoption through exclusive benefits.
- Reward loyal customers with enhanced loyalty programs.
- Optimize discount strategies to protect profit margins.
- Promote top-rated products more prominently.
- Target marketing campaigns toward high-revenue customer segments and express shipping users.

---

## Dashboard

The Power BI dashboard includes:

- Revenue Analysis
- Customer Segmentation
- Subscription Analysis
- Product Performance
- Age Group Analysis
- Shipping Comparison

---


## Future Improvements

- Customer Lifetime Value (CLV) prediction
- Customer churn prediction
- Product recommendation system
- Sales forecasting
- Interactive web dashboard using Streamlit

---

