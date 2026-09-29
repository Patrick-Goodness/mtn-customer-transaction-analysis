# MTN Customer & Transaction Analysis

## Project Overview

This project analyzes 1,500 MTN customer and transaction records using Microsoft Excel. The objective is to transform raw transaction data into reliable business insights covering revenue, customer activity, transaction performance, data plans, geographic activity, and monthly trends.

The project demonstrates an end-to-end analytics workflow: data cleaning, validation, transformation, exploratory analysis, KPI development, and dashboard reporting.

## Business Questions

- What is the total revenue generated?
- What is the average recharge value?
- Which data plans generate the most revenue?
- Which cities record the highest transaction activity and revenue?
- How does revenue change across months?
- What proportion of transactions are successful, failed, or pending?
- What is the average customer rating?
- How much data is consumed on average?
- How can transaction and customer information support operational decision-making?

## Dataset

The cleaned dataset contains **1,500 valid transactions**.

Key fields include:

- Transaction ID
- Transaction Date
- Network Provider
- Data Plan
- Recharge Amount
- Data Usage
- City
- Customer Rating
- Transaction Status

The original raw workbook contained inconsistent provider labels, missing values, and one malformed trailing record. The cleaning process removed the malformed record, standardized text and data types, preserved legitimate missing values, and created calculated revenue and monthly fields.

## Analysis Performed

The project includes:

- Data quality auditing
- Missing-value assessment
- Provider standardization
- Transaction-status validation
- Revenue analysis
- Data-plan performance analysis
- City-level analysis
- Monthly trend analysis
- Transaction-status analysis
- Customer rating analysis
- Data-usage analysis
- KPI development
- Excel dashboard reporting

## Key Findings

Based on the cleaned dataset:

- **Total transactions:** 1,500
- **Total recorded revenue:** ₦3,700,100
- **Average recharge:** approximately ₦2,597
- **Successful transactions:** 1,284
- **Transaction success rate:** 85.6%
- **Average customer rating:** 2.94/5
- **Average data usage:** approximately 13.30 GB

The workbook also identifies the highest-revenue data plan, highest-revenue city, and monthly revenue highs and lows through the analysis sheets and dashboard.

These findings are descriptive of the supplied dataset and should not be interpreted as representative of all MTN customers.

## Dashboard

The Excel dashboard presents:

- Total Revenue
- Total Transactions
- Success Rate
- Average Recharge
- Average Customer Rating
- Revenue by Data Plan
- Monthly Revenue Trend
- Transactions by City
- Transaction Status Distribution
- Key business observations

## Tools Used

- Microsoft Excel
- Excel formulas and data transformation
- Pivot-style analysis
- Data validation
- Charts and dashboard design

## Project Structure

- `MTN_Customer Transaction Analysis.xlsx` — formatted Excel analysis workbook
- `README.md` — project documentation

## Skills Demonstrated

**Data Analytics:** Data cleaning, validation, transformation, exploratory analysis, KPI analysis, trend analysis

**Excel:** Data preparation, aggregation, formulas, charts, dashboard design, business reporting

**Business Analysis:** Revenue analysis, transaction performance, geographic analysis, customer insights, operational reporting

## Limitations

The analysis is based only on the supplied dataset. Missing customer information was not artificially imputed, and the results are descriptive rather than statistically representative of MTN's entire customer base.

## Author

**Patrick Goodness**

Data Analyst | Excel | Power BI | SQL
