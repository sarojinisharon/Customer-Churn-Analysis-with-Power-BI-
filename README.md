# Customer Churn Analysis with Power BI  
Analyzing customer behavior to understand churn drivers and support better retention strategies.

## Project Overview

This project analyzes churn patterns in a fictional telecom company, Databel. Using Power BI, we explore how contract types, demographics, service usage, and payment methods influence customer retention. The goal is to equip stakeholders with interactive insights that help reduce churn and improve decision-making.

## Objectives

- Identify which customers are most likely to churn
- Understand key churn drivers across different segments
- Build a Power BI dashboard for real-time exploration
- Support business teams with visual, actionable intelligence

## Dataset Summary

The dataset contains detailed records for each customer, including:

- Churn status and churn reason
- Age, gender, and senior/under-30 flags
- Contract type (Month-to-Month, One Year, Two Year)
- Payment method, state, and group contract info
- Internet usage, international calls, and service charges

## Files in this Repository

| File | Description |
|------|-------------|
| `customer_churn.pbix` | Final Power BI dashboard with all visuals |
| `Databel - Data.csv` | Raw dataset used in the dashboard |

## Key Insights

- Month-to-month contracts have the highest churn rate
- Customers using paper checks tend to leave more often
- Unlimited data plans are associated with better retention
- Age and service usage trends show churn differences across groups

## How to Use

1. Clone or download this repository
2. Open the `customer_churn.pbix` file using Power BI Desktop
3. Use slicers and filters to interact with churn patterns by contract, payment, and demographic groups

## Tools Used

- Power BI
- DAX for calculated fields
- CSV data import

## Potential Next Steps

- Incorporate predictive churn modeling
- Add customer lifetime value metrics
- Automate churn alerting using Power BI service

