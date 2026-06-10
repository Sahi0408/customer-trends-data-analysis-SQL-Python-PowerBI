# Customer Shopping Behavior Analysis

> Uncovering retail insights through Python, SQL, and Power BI — from raw transactional data to actionable business strategy.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Project Workflow](#project-workflow)
- [Key Insights](#key-insights)
- [Power BI Dashboard](#power-bi-dashboard)
- [Business Recommendations](#business-recommendations)
- [Repository Structure](#repository-structure)
- [Skills Demonstrated](#skills-demonstrated)
- [Author](#author)

---

## Project Overview

This end-to-end data analytics project explores customer shopping behavior using real-world transactional retail data. The goal is to help a retail business make informed, data-driven decisions by analyzing spending patterns, product preferences, loyalty trends, subscription behavior, and discount usage.

The project covers the full analytics pipeline — data cleaning and preparation in Python, business analysis through SQL queries, and interactive visualization via a Power BI dashboard.

---

## Business Problem

A retail company needs answers to the following strategic questions:

- Which customers generate the most revenue?
- How do discounts influence purchasing decisions?
- Which products and categories perform best?
- Do subscribers bring more long-term value than non-subscribers?
- Which customer segments deserve the most marketing attention?

**Goal:** Improve sales, customer retention, and satisfaction through data-backed insights.

---

## Dataset

| Attribute | Details |
|-----------|---------|
| Total Records | 3,900 |
| Total Features | 18 |
| Missing Values | 37 (Review Rating column) |

**Data covers:**
- Customer demographics
- Purchase details and amounts
- Product categories
- Subscription status
- Discount and promo usage
- Review ratings
- Shipping preferences

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** (Pandas, NumPy) | Data cleaning, EDA, feature engineering |
| **PostgreSQL** | Business query analysis |
| **Power BI** | Dashboard development and visualization |
| **GitHub** | Version control and portfolio showcase |

---

## Project Workflow

### Step 1 — Data Cleaning & Preparation (Python)

- Imported and explored the raw dataset
- Filled missing Review Ratings using median imputation
- Standardized column names and data types
- Engineered new features: Age Groups, Purchase Frequency
- Validated data integrity before database loading
- Exported cleaned data to PostgreSQL

### Step 2 — Business Analysis (SQL)

Wrote targeted SQL queries to answer real business questions:

- Revenue breakdown by gender and age group
- High-spending discount users identification
- Top-rated products and categories
- Shipping type vs. average spend comparison
- Subscriber vs. non-subscriber revenue analysis
- Discount-dependent product detection
- RFM-based customer segmentation (Loyal / Returning / New)
- Repeat buyer analysis

### Step 3 — Dashboard & Visualization (Power BI)

Built an interactive Power BI dashboard covering:

- Revenue by category and age group
- Customer subscription status distribution
- Sales trends over time
- Product performance comparison

**KPIs tracked:** Total Customers · Average Purchase Amount · Average Review Rating

---

## Key Insights

**Gender Revenue:** Female customers generated slightly higher overall revenue than male customers.

**Discount Behavior:** A significant portion of high-spending customers still use discounts, suggesting room for premium or loyalty-based discount campaigns.

**Product Ratings:** Top-performing products consistently received strong customer reviews, indicating a clear link between product quality and repeat purchases.

**Shipping Preferences:** Customers who choose Express Shipping tend to spend more on average compared to Standard Shipping customers.

**Subscription Value:** Subscribers contribute disproportionately to total revenue and show stronger loyalty signals than non-subscribers.

**Customer Segments:** Segmenting customers into Loyal, Returning, and New categories enabled targeted retention strategies for each group.

---

## Power BI Dashboard

The dashboard allows stakeholders to interactively explore:

- Sales and revenue trends
- Customer demographic breakdowns
- Subscription and loyalty metrics
- Product and category performance
- Shipping preference impact on revenue

---

## Business Recommendations

| Area | Recommendation |
|------|---------------|
| **Subscriptions** | Introduce exclusive perks to convert one-time buyers into subscribers |
| **Loyalty Programs** | Reward high-frequency buyers to reduce churn |
| **Marketing** | Prioritize top-rated products in campaigns and promotions |
| **Discount Strategy** | Shift from blanket discounts to personalized offers for high-value segments |
| **Targeting** | Focus acquisition spend on age groups and segments with highest lifetime value |

---

## Repository Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── Data/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── Data_Cleaning_and_EDA.ipynb
│
├── SQL/
│   └── customer_behavior_sql_queries.sql
│
├── Dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── Reports/
│   ├── Business_Problem_Document.pdf
│   ├── Project_Report.pdf
│   └── Project_Presentation.pptx
│
└── README.md
```

---

## Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- SQL Query Writing & Business Analysis
- Customer Segmentation (RFM-based)
- Business Intelligence & KPI Tracking
- Dashboard Development (Power BI)
- Data Storytelling
- Business Recommendations from Data

---

## Author

**Sahul Patil**  
Aspiring Data Analyst · Python · SQL · Power BI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/your-username)
