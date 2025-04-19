# Bank-Loan-Analysis-Dashboard

## Table of Content

- [Project Overview](#Project-Overview)
- [Dataset Info](#Dataset-Info)
- [Tools Used](#Tools-Used)
- [Data Cleaning](#Data-Cleaning)
- [Analysis Objectives](#Analysis-Objectives)
- [Results](#Results)
- [Visualizations Used](#Visualizations-Used)
- [Limitations](#Limitations)
- [Recommendations](#Recommendations)
- [Conclusion](#Conclusion)

### Project Overview
This project provides a data-driven analysis of bank loan performance across several institutions using Power BI and Excel. It aims to uncover insights around loan approvals, defaults, repayment behaviors, and interest rate trends across demographics and employment statuses.

The interactive dashboard helps stakeholders understand how different banks and borrower segments behave—providing actionable insights for loan strategy, risk assessment, and policy planning.

### Dataset Info
The dataset contains 36,095 loan records with details such as:

- Bank Name
- Loan Status (Approved, Defaulted, Paid Off, Rejected)
- Customer Employment Type
- Loan Amount & Amount Paid
- Interest Rate
- State & Loan Purpose
- Loan Term (in years)

### Tools Used
- Power BI: for data modeling and dashboard creation

- Microsoft Excel: for initial data review and structure

- DAX: for calculated columns and measures

- Power Query: for data transformation and cleaning

### Data Cleaning
Data was cleaned using Power BI's Power Query Editor. Key tasks included:

- Removing null or irrelevant rows
- Standardizing text fields (e.g., Loan Status, Employment Type)
- Converting numeric strings to proper data types
- Formatting date fields
- Creating new measures with DAX for interest rates, customer count, etc.

### Analysis Objectives
- Understand loan performance by bank and loan status

- Analyze monthly trends in loan repayment

- Evaluate how employment type and loan purpose influence repayment

- Compare interest rates by bank and loan status

- Provide actionable insights to reduce default rates

### Results
1. Highest Loan Defaults: GTBank and Polaris Bank had high loan disbursement, but also notable default rates.

2. Repayment Trends: Loans issued earlier in the year had lower average repayments than those from mid-year.

3. Interest Rate Observations: Stanbic IBTC had the highest average interest rate at 23.10%, while Polaris had the lowest.

4. Purpose-wise Analysis: Loans for debt consolidation and personal use were the most frequent, hinting at high consumer credit dependency.

5. Loan Term Trends: 2 and 3 year loans dominated the portfolio with a near-equal share of loan statuses.

### Visualizations Used
- Bar Charts: Loan by Purpose, Loan Amount by Bank

- Line Charts: Monthly Repayment Trends

- Donut Charts: Interest Rate by Loan Status, Loan by Term

- Matrix Table: Loan Status Summary with KPIs

- Cards: Total Loan Amount, Customers, Amount Paid, Average Interest Rate

- Slicers: Bank, Loan Status, Employment, State

### Limitations
- Time-based trends were only analyzed at the monthly level; no daily or quarterly granularity.
- Some states or banks had incomplete loan records, which might affect accuracy.
- Loan approval criteria were not included, so deeper risk modeling wasn't possible.

### Recommendations
- Focus risk mitigation strategies on high-default banks and employment types.

- Reassess interest rates for loan categories with high defaults despite higher income.

- Improve education around loan purposes with poor repayment behavior (e.g., personal, medical).

- Regularly update datasets to reflect evolving trends.

### Conclusion
This dashboard demonstrates how financial institutions can leverage data analytics to monitor and improve loan performance, target customer segments, and optimize lending practices. 
