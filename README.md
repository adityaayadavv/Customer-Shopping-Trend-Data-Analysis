# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior using Python, SQL, and Power BI to uncover insights related to customer preferences, spending patterns, subscription behavior, and product performance.

The objective of this project is to help businesses make data-driven decisions by identifying trends in customer purchases, product categories, discounts, subscriptions, and demographics.

The project includes:
- Data loading and preprocessing using Python
- Exploratory Data Analysis (EDA)
- Data cleaning and feature engineering
- SQL analysis using PostgreSQL/MySQL/SQL Server
- Interactive Power BI dashboard creation
- Business report and presentation development using Gamma

---

# Dataset

The dataset contains customer shopping transaction data with information related to:
- Customer demographics
- Purchase details
- Product categories
- Reviews and ratings
- Discounts and promo usage
- Shipping preferences
- Subscription status
- Purchase frequency

### Dataset Summary
- Total Records: 3,900
- Total Features: 18
- Missing Values: 37 values in the review rating column

---

# Tools & Technologies

| Tool | Purpose |
|------|----------|
| Python | Data cleaning, preprocessing, EDA |
| Pandas & NumPy | Data manipulation |
| Data visualization |
| PostgreSQL / MySQL / SQL Server | SQL analysis |
| Power BI | Dashboard creation |
| Gamma | Presentation creation |
| Jupyter Notebook | Development environment |

---

# Project Workflow

## 1. Data Loading & Cleaning
The dataset was imported into Python using Pandas for preprocessing and transformation.

Tasks performed:
- Loaded dataset into Python
- Checked dataset structure and summary statistics
- Handled missing values using median imputation
- Renamed columns into snake_case format
- Removed redundant columns
- Verified data consistency

---

## 2. Feature Engineering
Additional features were created to improve analysis:
- `age_group`
- `purchase_frequency_days`

These features helped in customer segmentation and behavior analysis.

---

## 3. Exploratory Data Analysis (EDA)

EDA was performed to identify:
- Customer spending behavior
- Revenue trends
- Product category performance
- Subscription trends
- Shipping preferences
- Customer purchase patterns

---

# SQL Analysis

SQL queries were written and executed in PostgreSQL/MySQL/SQL Server to answer important business questions.

### Key Business Queries
- Revenue by gender
- High-spending discount users
- Top-rated products
- Shipping type comparison
- Subscribers vs non-subscribers analysis
- Discount-dependent products
- Customer segmentation
- Revenue by age group
- Repeat buyers analysis
- Top products by category

---

# Power BI Dashboard

An interactive Power BI dashboard was created to visualize customer shopping behavior and business insights.

## Dashboard Features
- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status Analysis

## Interactive Filters
- Gender
- Category
- Shipping Type
- Subscription Status

---

# Key Insights

- Male customers generated higher revenue compared to female customers.
- Clothing category generated the highest sales and revenue.
- Non-subscribers contributed the largest share of customers and revenue.
- Express shipping customers showed slightly higher average spending.
- Loyal customers formed the largest customer segment.
- Young adults contributed the highest revenue among all age groups.

---

# Business Recommendations

- Promote subscription-based benefits to increase customer retention.
- Introduce stronger customer loyalty programs.
- Optimize discount strategies to maintain profitability.
- Focus marketing efforts on high-revenue customer segments.
- Highlight top-rated and best-selling products in campaigns.


---

# Deliverables

- Python Data Analysis Notebook
- SQL Query Scripts
- Power BI Dashboard
- Project Report
- Gamma Presentation

---

# Conclusion

This project demonstrates a complete end-to-end data analytics workflow involving:
- Data cleaning
- Exploratory Data Analysis
- SQL business analysis
- Dashboard development
- Business reporting

The insights generated from this analysis can help businesses better understand customer behavior, improve engagement strategies, and make informed business decisions.
