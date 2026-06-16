# Order Records - Exploratory Data Analysis (EDA)

## Overview
This project is the second phase of a data analytics internship at DecodeLabs. 
After cleaning the order records dataset in Project 1, this notebook digs into 
the data to find patterns, trends, and insights that tell a real business story.

## Dataset
- 1,200 order records spanning January 2023 to June 2025
- 14 columns covering products, pricing, payment methods, order status, and referral sources

## What's Inside the Notebook
- Descriptive statistics across all numeric columns
- Outlier detection using the IQR method
- Categorical breakdown of products, payment methods, order status, and referral sources
- Monthly trend analysis of orders and revenue over time
- Correlation analysis between key numeric variables

## Key Findings
- Product price is the biggest driver of revenue, stronger than order quantity
- Cancellations and returns outnumber delivered orders, a major operational red flag
- Order volume has gradually declined from 2023 into 2025, with signs of recovery mid-2025
- Instagram is the top customer acquisition channel
- 8 high-value outlier orders were identified as legitimate bulk purchases, not errors

## Tools Used
- Python 3
- pandas
- Jupyter Notebook

## Author
Daniel | DecodeLabs Data Analytics Internship, Batch 2026
