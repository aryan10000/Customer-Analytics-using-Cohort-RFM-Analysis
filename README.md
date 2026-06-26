# Customer Segmentation & Retention Analytics

End-to-end customer analytics project using the **Olist Brazilian E-Commerce Dataset**. This project combines **Cohort Analysis** and **RFM (Recency, Frequency, Monetary) Analysis** to evaluate customer retention, identify high-value customer segments, and generate actionable business recommendations for improving customer lifetime value.

<br>

### Cohort Heatmap
<p align="center">
<img width="891" height="558" alt="Screenshot 2026-06-26 at 11 50 27 AM" src="https://github.com/user-attachments/assets/450bd298-732d-4bdd-87e0-f5b8b3e618a1" />

</p>

---

## Project Highlights

* Analyzed **99K+ e-commerce orders** from the Olist Brazilian marketplace.
* Built **monthly customer cohorts** to evaluate retention over time.
* Segmented customers into **7 business-oriented RFM segments**.
* Identified high-value, loyal, and churn-risk customers.
* Generated actionable recommendations to improve retention and customer lifetime value.

---

# Project Overview

Customer acquisition alone is not enough for sustainable business growth. Companies must understand **how well customers are retained**, **which customers generate the most value**, and **which customer groups are at risk of churning**.

This project combines two complementary analytical techniques:

* **Cohort Analysis** to measure customer retention over time.
* **RFM Analysis** to identify valuable customer segments based on purchasing behavior.

Together, these analyses provide a comprehensive understanding of customer engagement and highlight opportunities to improve retention, increase repeat purchases, and maximize revenue.

---

# Business Objectives

The project answers the following business questions:

* How effectively does the business retain customers after their first purchase?
* Which customer segments generate the highest revenue?
* Which customers are most likely to churn?
* Which customers should be prioritized for retention campaigns?
* How can customer lifetime value be improved?

---

# Dataset

**Dataset:** Olist Brazilian E-Commerce Dataset

Dataset Size

* 99,441 Orders
* 96,096 Customers
* 112,650 Order Items
* Period: 2016–2018


The dataset contains transactional information across multiple relational tables, including:

* Customers
* Orders
* Order Items
* Payments
* Products
* Sellers

Customer-level features were engineered by combining relevant tables to support retention and segmentation analyses.

---

# Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Analytical Techniques

* Feature Engineering
* Customer Cohort Analysis
* RFM Segmentation
* Customer Retention Analysis
* Customer Behavior Analysis

---

# Project Workflow

```text
Raw Data
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Feature Engineering
      │
      ├──────────────► Cohort Analysis
      │                     │
      │                     ▼
      │              Customer Retention
      │
      └──────────────► RFM Analysis
                            │
                            ▼
                 Customer Segmentation
                            │
                            ▼
                 Business Recommendations
```

---

# Part 1 — Cohort Analysis

## Objective

Measure customer retention across monthly acquisition cohorts to understand repeat purchasing behavior over time.

### Methodology

* Identified each customer's first purchase month.
* Grouped customers into monthly cohorts.
* Calculated monthly retention percentages.
* Generated retention heatmaps and weighted retention metrics.

### Key Findings

* Customer retention declines sharply after the first purchase.
* **96.88%** of customers placed only a single order.
* Only **0.48%** of customers returned during the month following their first purchase.
* Retention remained consistently low across all cohorts, indicating a structural retention challenge rather than a problem isolated to specific acquisition periods.

### Visualization

### Cohort Heatmap
<p align="center">
<img width="891" height="558" alt="Screenshot 2026-06-26 at 11 50 27 AM" src="https://github.com/user-attachments/assets/e1c10ebd-ea52-4981-ad0a-638ab6559e7d" />

</p>

---

# Part 2 — RFM Analysis

## Objective

Segment customers based on purchasing behavior using:

* **Recency** – Days since last purchase
* **Frequency** – Number of purchases
* **Monetary** – Total customer spending

Customers were classified into the following business segments:

* Champions
* Loyal Customers
* Potential Loyalists
* At Risk High Value
* At Risk
* Lost
* Others

---

## Customer Distribution

Nearly **40%** of customers are classified as **Potential Loyalists**, while another **40%** fall into the **Lost** segment. Only a very small percentage qualify as **Champions** or **Loyal Customers**, highlighting limited long-term customer loyalty.

<p align="center">
<img width="3068" height="1403" alt="Customer Distribution by Segment" src="https://github.com/user-attachments/assets/032e44d6-95f8-4743-800b-65bbd5998755" />


</p>

---

## Revenue Contribution

Although Champions represent only a small proportion of the customer base, they generate significantly higher revenue per customer compared to other segments.

<p align="center">
<img width="2962" height="1403" alt="Revenue Contribution by Segment" src="https://github.com/user-attachments/assets/27d81f61-a1b6-4a77-9719-31b19d0ff60d" />

</p>

---

## Customer Behavior by Segment

The visualizations below compare average spending and purchasing recency across customer segments.

<p align="center">
<img width="3015" height="1403" alt="Average Monetary Value by Segment" src="https://github.com/user-attachments/assets/41c55452-9da9-47ec-9bf6-4ac49c3ccfd5" />

</p>

<br>

<p align="center">
<img width="3015" height="1403" alt="Average Recency by Segment" src="https://github.com/user-attachments/assets/4b2ed646-fb05-45b6-9227-a14e214c00e1" />

</p>

---

# Key Business Insights

* Customer acquisition is considerably stronger than customer retention.
* Repeat purchasing behavior is extremely limited across the customer base.
* High-value customers contribute a disproportionately large share of revenue.
* Potential Loyalists represent the largest opportunity for future revenue growth.
* Customer retention initiatives are likely to deliver greater long-term value than focusing solely on acquiring new customers.

---

# Business Recommendations

* Introduce loyalty and rewards programs to encourage second and third purchases.
* Launch personalized email, SMS, and remarketing campaigns targeting Potential Loyalists before they churn.
* Develop win-back campaigns for Lost customers using personalized incentives.
* Prioritize retention strategies for At Risk High Value customers to prevent revenue loss.
* Reward Champions and Loyal Customers with exclusive benefits and personalized offers to maximize customer lifetime value.

---


# Conclusion

This project demonstrates how customer analytics techniques can transform raw transactional data into actionable business insights.

By combining **Cohort Analysis** with **RFM Segmentation**, the analysis reveals that while customer acquisition is strong, repeat purchasing and long-term retention remain major challenges. The findings provide a data-driven foundation for designing retention strategies, prioritizing high-value customers, and improving customer lifetime value through targeted marketing initiatives.
