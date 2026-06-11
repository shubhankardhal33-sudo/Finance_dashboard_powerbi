# Finance Transaction Dashboard — Power BI

## Overview
An interactive 2-page finance dashboard built on a Kaggle 
transaction dataset. Features a dynamic KPI selector built 
with DAX SWITCH() that toggles all visuals between 
Total Revenue, Total Fees, and Total Tax simultaneously.

## Dashboard Preview
<img width="1317" height="715" alt="Screenshot 2026-06-11 201623" src="https://github.com/user-attachments/assets/ce1f62c8-007f-4198-9d00-567b48e195ec" />
<img width="1325" height="710" alt="Screenshot 2026-06-11 201722" src="https://github.com/user-attachments/assets/aa4dea73-f3db-4376-b76a-6e5391546b90" />

## Key Features
- Dynamic metric slicer using DAX SWITCH() + SELECTEDVALUE()
- KPIs: Total Amount, Total Transactions, Avg Transaction, Total Tax
- Customer segmentation by gender, occupation, and state
- Transaction status breakdown (donut chart)
- Monthly trend analysis (area chart)
- Detailed transaction log table with 10 columns
- Custom calendar table for time intelligence

## Tools Used
- Power BI Desktop
- DAX (SWITCH, SELECTEDVALUE, CALCULATE)
- Data source: Kaggle Finance Transactions Dataset

## Data Model
4 tables: finance_transactions, customers, 
calendar table, Dynamic metric 
