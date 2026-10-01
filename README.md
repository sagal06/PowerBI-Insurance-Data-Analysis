# PowerBI-Insurance-Data-Analysis

## Project Overview

An interactive insurance analytics report built in Power BI to analyze premiums, coverage amounts, claims, policy types, claim status, customer information, and policy activity. The report includes interactive slicers, KPI cards, categorical and trend visualizations, matrix analysis, and a drill-through detail page.

## Objectives

- Analyze insurance premiums and coverage amounts
- Analyze claim amounts and claim status
- Compare different policy types
- Analyze policy activity
- Explore customer and claim information
- Provide interactive filtering and drill-through analysis

## Tools Used

- Microsoft Power BI
- Power Query
- Power BI Service

## Dashboard Visuals
![Dashboard](Dashboard/Overview.png)

### KPI Cards
- Total Claim Amount — Sum of ClaimAmount
- Total Coverage Amount — Sum of CoverageAmount
- Total Premium Amount — Sum of PremiumAmount

### Bar Chart
- Axis: PolicyType
- Values: Sum of PremiumAmount
- Purpose: Compare premium amounts across policy types

### Donut Chart
- Category: Active/Inactive
- Values: Count of Active/Inactive
- Purpose: Show the distribution of active and inactive policies

### Ribbon Chart
- Category: ClaimStatus
- Values: Count of ClaimStatus
- Purpose: Analyze the number of claims by claim status

### Line Chart
- Axis: Age Group
- Values: Sum of ClaimAmount
- Purpose: Compare claim amounts across age groups

### Matrix
- Rows: PolicyType
- Columns: ClaimStatus
- Values: Sum of CoverageAmount
- Purpose: Compare coverage amounts across policy types and claim statuses

### Slicers
- PolicyNumber
- ClaimNumber
- CustomerID

### Drill-through
- Drill-through field: PolicyType
- Detailed page contains policy, customer, claim, demographic,
  coverage, premium, and date information.

## Power BI Service

- Published report to Power BI Service
- Configured scheduled refresh
- Worked with Power BI reports and dashboards

## Dataset

The dataset was provided as part of the Udemy course
"Complete Data Analyst Bootcamp From Basics To Advanced"
by Krish Naik and Jayant Topnani.

The original course dataset is not redistributed in this repository.

## Project Type

Guided Power BI project completed as part of my Data Analyst training.
