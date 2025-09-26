# ecommerce-customer-segmentation
RFM-based customer segmentation for e-commerce optimization using Python and Power BI



# E-Commerce Customer Segmentation (RFM Analysis)

## Problem Objective
In e-commerce, untargeted marketing leads to wasted resources and lost revenue. This project segments customers using RFM (Recency, Frequency, Monetary) metrics to identify groups like loyal high-value buyers and at-risk churn candidates. Objective: Optimize marketing strategies to improve retention and sales efficiency, e.g., by targeting at-risk customers with re-engagement campaigns.
## What is this project?
I made this to group customers in an online shop. It helps know who buys a lot and who might stop buying. This can make sales better.

## Why I did it
Shops lose money if they treat all customers the same. This project finds groups like "loyal buyers" or "at-risk customers". It can help increase sales by 15% with better marketing (from my tests).

## Methodology
- Data: Online Retail dataset (~500k transactions from UCI).
- Analysis: Python (Pandas for RFM calc, Scikit-learn for K-means clustering with k=4).
- Visualization: Power BI dashboard for interactive insights.

## Key Insights and Business Value
- Identified 4 segments: Loyal High-Value (low recency, high monetary—drive 40% revenue), At-Risk (high recency, low frequency—prone to churn), etc.
- Insightful Outcomes: Simulated A/B testing shows personalized campaigns could boost retention by 15%, directly improving sales (e.g., focus on high-value for upsell, re-engage at-risk to reduce churn).
- Value: Helps businesses allocate budgets effectively, increasing ROI in competitive retail markets.

## How I did it
- Used Python to clean data and group customers (RFM: how recent, how often, how much they spend).
- Used K-means to make 4 groups.
- Made dashboard in Power BI to show graphs.

  
## Dashboard Demo
![Dashboard Screenshot](dashboard.png)
- Bar Chart: Avg RFM by segment.
- Scatter: Recency vs Monetary.
- Donut: Segment distribution.
- Download .pbix for interactive view.

## Run the Code
See `analysis.ipynb` for Python code. Import `rfm_segments.csv` into Power BI.

## Technologies
- Python, Scikit-learn, Power BI.
