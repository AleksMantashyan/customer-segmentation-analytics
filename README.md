# Customer Segmentation Analytics

This repository contains a business analytics project that analyzes one year of transaction data from an online retailer to understand customer behavior, identify high-value customers, and evaluate whether personalized marketing strategies improve conversion rates.

The project follows a clear analytical flow:
**business problem → data → analysis → insights → decisions**.

------------------------------------------------------------

## Repository Structure

customer-segmentation-marketing-analytics/
│
├── data/
│   └── sales_transaction.csv
│
├── notebook/
│   └── customer_analytics.ipynb
│
├── report/
│   └── final_report.pdf
│
├── presentation/
│   └── final_presentation.pdf
│
└── README.md

------------------------------------------------------------

## Files Overview

### data/sales_transaction.csv
Raw transaction-level dataset used for the analysis.  
Each row represents a purchased product and includes:
- Transaction number  
- Date  
- Product  
- Price  
- Quantity  
- Customer ID  
- Country  

The dataset was cleaned in the notebook by removing cancelled orders, invalid quantities or prices, and rows with missing customer IDs.

------------------------------------------------------------

### notebook/customer_analytics.ipynb
Jupyter Notebook containing the complete analysis, including:
- Data cleaning and preprocessing  
- RFM (Recency, Frequency, Monetary) analysis  
- K-Means customer segmentation  
- KNN classification to validate clusters  
- Customer Lifetime Value (CLV) estimation  
- Logistic regression to identify high-value customers  
- A/B test simulation comparing generic vs personalized offers  
- Statistical testing (chi-square test, t-test, confidence intervals)  
- Visualizations used for interpretation  

------------------------------------------------------------

### report/final_report.pdf
Final written report describing:
- Business motivation and research questions  
- Methodology and modeling choices  
- Key results and interpretations  
- SWOT analysis  
- Business recommendations and limitations  

------------------------------------------------------------

### presentation/final_presentation.pdf
Presentation slides summarizing the project with:
- Key findings and visuals  
- Model results  
- Business insights and decisions  

------------------------------------------------------------

## Summary

- One dataset, one notebook, one report, and one presentation  
- Focus on customer segmentation, prediction, and marketing effectiveness  
- Results support targeted retention and personalization strategies  

This repository contains everything needed to review and understand the project.
