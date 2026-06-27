# Customer RFM & Cohort Analytics

### Customer Segmentation • Retention Analysis • Business Intelligence

An end-to-end customer analytics project built using the **Olist Brazilian E-Commerce Dataset**. This project combines **Cohort Analysis** and **RFM (Recency, Frequency, Monetary) Segmentation** to measure customer retention, identify high-value customer groups, and generate actionable business recommendations for improving customer lifetime value (CLV).

The project includes Python-based data preprocessing and analysis, followed by an executive-level **Power BI dashboard** for interactive business reporting.

---

# Executive Dashboard

<p align="center">

<img width="879" height="494" alt="new cohort rfm" src="https://github.com/user-attachments/assets/fa94a123-265e-4399-b129-687d0eb7e18c" />


</p>

| Orders | Customers | Period | BI Tool | Analysis |
|--------|-----------|--------|---------|----------|
| 99,441 | 96,096 | 2016–2018 | Power BI | Cohort + RFM |

---

# Executive Summary

Using transactional data from over **99K orders** and **96K customers**, this project evaluates customer behavior through two complementary analytical techniques:

- **Cohort Analysis** to measure customer retention over time.
- **RFM Segmentation** to classify customers based on purchasing behavior.

The analysis reveals that while customer acquisition is strong, customer retention remains a significant challenge. **96.88%** of customers purchase only once, highlighting substantial opportunities to improve repeat purchasing and customer lifetime value through targeted retention strategies.

---

# Business Problem

Acquiring customers is only the first step toward sustainable growth.

Businesses must understand:

- How effectively customers are retained
- Which customers generate the highest revenue
- Which customer groups are at risk of churning
- Which segments should be prioritized for marketing investment

This project addresses these business questions using customer analytics techniques and presents the results through an interactive Power BI dashboard.

---

# Project Highlights

- Analyzed **99,441 e-commerce orders** across **96,096 unique customers**
- Engineered customer-level analytical features from multiple relational datasets
- Built monthly customer cohorts to evaluate long-term retention
- Segmented customers into **7 business-focused RFM segments**
- Developed an executive Power BI dashboard with interactive filters
- Generated business recommendations based on customer purchasing behavior

---

# Dashboard Overview

The Power BI dashboard provides an executive overview of customer performance through:

- Executive KPI cards
- Monthly revenue trend
- Monthly customer acquisition trend
- Customer distribution by segment
- Average revenue by customer segment
- Customer retention trend
- Geographic customer distribution
- Payment method analysis
- RFM segment performance summary

---

# Key Business Insights

### Customer Retention

- **96.88%** of customers placed only a single order.
- Month-1 weighted retention is only **0.48%**.
- Customer retention declines sharply after the first purchase across all acquisition cohorts.

### Customer Segmentation

- Nearly **40%** of customers belong to the **Potential Loyalist** segment.
- Another **40%** are classified as **Lost** customers.
- **Champions** represent a very small portion of the customer base but generate significantly higher revenue per customer.

### Revenue

- Revenue is highly concentrated among high-value customer segments.
- Customer acquisition is healthy, but limited repeat purchasing constrains long-term revenue growth.

---

# Business Recommendations

- Develop loyalty programs to encourage repeat purchases.
- Target **Potential Loyalists** with personalized promotions before they churn.
- Launch win-back campaigns for **Lost Customers**.
- Prioritize retention initiatives for **At Risk High Value** customers.
- Reward **Champions** and **Loyal Customers** with exclusive offers to maximize lifetime value.

---

# Dataset

**Dataset:** [Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)


### Dataset Summary

| Metric | Value |
|---------|-------|
| Customers | 96,096 |
| Orders | 99,441 |
| Order Items | 112,650 |
| Analysis Period | 2016 – 2018 |

The project integrates multiple relational tables including:

- Customers
- Orders
- Order Items
- Payments
- Products
- Sellers

Customer-level analytical features were engineered by joining relevant tables and aggregating transactional data.

---

# Tech Stack

| Category | Tools |
|----------|-------|
| **Programming** | Python, SQL, Pandas, NumPy |
| **Visualization** | Power BI, Matplotlib, Seaborn |
| **Analytics** | Cohort Analysis, RFM Segmentation, Customer Retention Analysis |
| **Data Processing** | Data Cleaning, Feature Engineering, Exploratory Data Analysis (EDA) |


---


# Project Workflow

```text
Raw Transaction Data
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Feature Engineering
        │
        ├────────────► Cohort Analysis
        │                    │
        │                    ▼
        │             Customer Retention
        │
        └────────────► RFM Analysis
                             │
                             ▼
                  Customer Segmentation
                             │
                             ▼
                 Business Insights & Recommendations
                             │
                             ▼
                Interactive Power BI Dashboard
```

---

# Cohort Analysis

## Objective

Measure customer retention across monthly acquisition cohorts to understand repeat purchasing behavior over time.

---

## Methodology

- Identified each customer's first purchase month.
- Assigned customers into monthly acquisition cohorts.
- Calculated monthly retention percentages.
- Generated weighted retention metrics.
- Visualized retention using cohort heatmaps.

---

## Cohort Heatmap

<p align="center">

<img width="891" height="558" alt="Screenshot 2026-06-26 at 11 50 27 AM" src="https://github.com/user-attachments/assets/78f36754-e6db-4d70-837b-56585c8a83e8" />


</p>

---

## Key Findings

- Customer retention declines sharply immediately after the first purchase.
- Only **0.48%** of customers return during the month following their first purchase.
- Retention remains consistently low across all acquisition cohorts, indicating a structural retention challenge rather than seasonal variation.

---

# RFM Analysis

## Objective

Segment customers based on purchasing behavior using three behavioral metrics:

- **Recency** – Days since last purchase
- **Frequency** – Number of completed purchases
- **Monetary** – Total customer spending

Customers were classified into the following business segments:

- Champions
- Loyal Customers
- Potential Loyalists
- At Risk High Value
- At Risk
- Lost
- Others

---

## Customer Distribution

Nearly **40%** of customers belong to the **Potential Loyalist** segment, while another **40%** are classified as **Lost** customers. Only a small proportion qualify as **Champions** or **Loyal Customers**, highlighting limited long-term customer loyalty.

<p align="center">

<img width="3068" height="1403" alt="Customer Distribution by Segment" src="https://github.com/user-attachments/assets/b59a844c-4821-416e-a557-c07f21b003fc" />


</p>

---

## Revenue Contribution

Although **Champions** represent a relatively small customer segment, they contribute substantially higher revenue per customer compared to other segments.

<p align="center">

<img width="2962" height="1403" alt="Revenue Contribution by Segment" src="https://github.com/user-attachments/assets/fe60bb7f-cd95-4db4-8962-f4ee28d6d932" />


</p>

---

## Customer Behavior

The visualizations below compare customer spending and purchasing behavior across RFM segments.

<p align="center">

<img width="3015" height="1403" alt="Average Monetary Value by Segment" src="https://github.com/user-attachments/assets/2cd032f0-21c2-4d27-8086-1fd01d7bc2cb" />


</p>

---

# Power BI Dashboard

The final Power BI dashboard integrates all key analyses into a single executive report.

<img width="879" height="494" alt="new cohort rfm" src="https://github.com/user-attachments/assets/b3b89794-6796-45ae-a715-e39680ce0427" />



### Dashboard Features

- Revenue KPIs
- Customer KPIs
- Monthly Revenue Trend
- Monthly Customer Acquisition
- Customer Distribution by Segment
- Average Revenue by Segment
- Payment Method Analysis
- Geographic Customer Distribution
- Customer Retention Trend
- Interactive Filters
- RFM Performance Summary

---

# Business Impact

This analysis helped identify key opportunities to improve customer retention and maximize customer lifetime value.

- Identified extremely low Month-1 customer retention (0.48%).
- Segmented 96K customers into seven actionable RFM groups.
- Highlighted high-value customers for loyalty initiatives.
- Identified churn-risk customers for targeted retention campaigns.
- Built an executive dashboard for interactive customer performance analysis.
  
---

# Skills Demonstrated

- Customer Analytics
- Cohort Analysis
- RFM Segmentation
- Power BI
- Python
- SQL
- Pandas
- Business Intelligence
- Dashboard Design
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization

---

# Conclusion

This project demonstrates an end-to-end customer analytics workflow using Python and Power BI. By combining Cohort Analysis with RFM Segmentation, it uncovers key retention challenges, identifies high-value customer segments, and provides data-driven recommendations to improve customer lifetime value.
