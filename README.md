# Customer Behaviour & Business Performance Analysis
### AnalystLab Africa — Data Analytics Internship, Week 1

## Overview
Junior Data Analyst project for AnalystLab Africa Consulting, engaged by (fictional) client
ABC Communications Ltd to investigate customer churn and provide business insights that
support customer retention strategies.

## Business Questions
1. What does the customer base look like?
2. Which segments have the highest churn?
3. Does contract type influence retention?
4. Does tenure affect loyalty?
5. Which services influence churn?
6. Which payment methods have higher churn?
7. What actions should management take?

## Dataset
[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
— 7,043 customers, 21 fields (demographics, account info, services subscribed, churn status).

## Method
1. **Data Inspection** — checked structure, data types, missing values, and duplicates.
   Found 11 records with blank `TotalCharges` (all new customers with `tenure = 0`).
2. **Exploratory Analysis** — built bar charts, pie charts, histograms, a box plot, and a
   correlation heatmap to explore churn by contract type, internet service, payment method,
   tenure, and monthly charges.
3. **Insights & Recommendations** — translated findings into business risks, opportunities,
   and actionable recommendations for the retention team.

## Key Findings
- Overall churn rate: **26.5%**
- Month-to-month contracts churn at **42.7%** vs **2.8%** for two-year contracts
- Fiber optic internet churns at **41.9%**, the highest of any service tier
- Electronic check payers churn at **45.3%**, well above automatic payment methods
- Churned customers have a shorter average tenure (18.0 months) than retained customers (37.6 months)

## Repository Contents
| File | Description |
|---|---|
| `AnalystLab Week1.xlsx` | Dataset inspection, all required charts with interpretations, insights & recommendations |
| `Business Understanding Report.docx` | 1–2 page business understanding writeup |
| `Dataset Inspection Report.docx` | Detailed report on rows, columns, data types, missing values, and duplicates |
| `AnalystLab Week1 Presentation.pptx` | Business presentation summarising findings |


## Author
**Samantha Rukwaro**
Junior Data Analyst Intern, AnalystLab Africa Consulting
[LinkedIn](https://linkedin.com/in/samantha-rukwaro-78912b365)
