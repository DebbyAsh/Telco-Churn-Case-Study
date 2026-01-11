# Telco Customer Churn Analysis

## Project Overview

This project presents an end-to-end customer churn analysis using a
real-world inspired telecom dataset. The goal is to understand why
customers leave, build predictive models to identify at-risk customers,
and translate analytical findings into actionable business
recommendations.

The project demonstrates both technical data science skills and strong
business reasoning, which are essential for real-world analytics roles.

------------------------------------------------------------------------

## Business Problem

Customer churn leads to lost revenue and increased customer acquisition
costs. In highly competitive subscription-based industries (such as
telecom, banking, SaaS, and streaming services), retaining customers is
often more cost-effective than acquiring new ones.

**Objective:** - Understand key drivers of churn\
- Build predictive models to identify customers likely to leave\
- Provide practical recommendations to reduce churn and improve customer
retention

------------------------------------------------------------------------

## Dataset

Telco Customer Churn Dataset\
Each row represents a customer with information on: - Demographics
(e.g. gender, senior citizen, dependents) - Services subscribed
(internet, streaming, tech support, etc.) - Contract type and payment
method - Tenure and billing information - Target variable: `Churn` (1 =
customer left, 0 = customer stayed)

------------------------------------------------------------------------

## Project Workflow

The analysis follows a structured data science workflow:

1.  Problem Framing\
2.  Data Cleaning & Preparation\
3.  Exploratory Data Analysis (EDA)\
4.  Feature Engineering\
5.  Encoding & Preprocessing\
6.  Model Building (Logistic Regression & Random Forest)\
7.  Model Evaluation (Confusion Matrix, ROC-AUC, Precision, Recall,
    F1-score)\
8.  Threshold Optimization & Precision--Recall Analysis\
9.  Business Recommendations 

------------------------------------------------------------------------

## Key Insights

-   New customers (short tenure) are significantly more likely to churn\
-   Month-to-month contracts show much higher churn than long-term
    contracts\
-   Higher monthly charges are associated with increased churn risk\
-   Customers using fewer services tend to churn more\
-   Logistic Regression achieved strong performance (ROC-AUC ≈ 0.86) and
    performed slightly better than Random Forest for identifying
    churners

------------------------------------------------------------------------

## Model Performance (Summary)

-   Logistic Regression ROC-AUC: \~0.86\
-   Random Forest ROC-AUC: \~0.85\
-   The models demonstrate strong ability to distinguish churners from
    non-churners\
-   Recall was prioritized to better capture at-risk customers

------------------------------------------------------------------------

## Business Recommendations

-   Prioritize high-risk customers predicted by the model for retention
    efforts\
-   Strengthen onboarding and engagement during the first 6 months\
-   Encourage customers to move from month-to-month to long-term
    contracts\
-   Review pricing and perceived value for high-paying customers\
-   Use churn probability scores to drive targeted retention campaigns
------------------------------------------------------------------------

## Repository Structure

-   `notebook/` -- Telco Churn Analysis.ipynb
-   `data/` -- churn.csv
-   `README.md` -- Project overview and documentation

------------------------------------------------------------------------

## Why This Project Matters

Churn prediction is one of the most common real-world analytics
problems. This project demonstrates: - Business understanding\
- Structured analytical thinking\
- End-to-end machine learning workflow\
- Clear communication of insights\
- Practical, actionable recommendations

------------------------------------------------------------------------


