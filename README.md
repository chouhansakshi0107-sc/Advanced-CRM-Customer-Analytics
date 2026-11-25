# Advanced CRM & Customer Analytics System

An end-to-end Customer Relationship Management (CRM) analytics project developed using Python, Pandas, NumPy, Matplotlib, Seaborn, Microsoft Excel, and Google Colab.

This project analyses customer information, transactions, products, customer interactions, and support tickets to understand customer behaviour, purchasing patterns, retention, and support performance.

> **Note:** All datasets used in this project are synthetic and created for learning and portfolio demonstration. They do not represent real company data.

---

## 1. Project Overview

The Advanced CRM & Customer Analytics System demonstrates how data analytics can help businesses understand their customers and improve business decision-making.

The project covers:
- Customer demographics analysis
- Transaction and revenue analysis
- Product performance analysis
- RFM customer segmentation
- Customer retention and churn-risk analysis
- Customer interaction analysis
- Customer support performance
- Python dashboard and data visualisation

## 2. Business Problem

Businesses need to understand their customers, purchasing behaviour, customer loyalty, and support-service performance.

This project combines multiple datasets to identify customer patterns, analyse revenue, understand customer retention, and evaluate customer support operations.

## 3. Project Objectives

1. Clean and preprocess multiple datasets.
2. Analyse customer demographics and purchasing behaviour.
3. Evaluate revenue and product performance.
4. Segment customers using the RFM model.
5. Analyse repeat purchases and customer retention.
6. Identify customers with higher inactivity risk.
7. Evaluate customer satisfaction and support-ticket performance.
8. Create meaningful business visualisations.

## 4. Tools and Technologies

1. Python - Data analysis.
2. Pandas - Data cleaning and manipulation. 
3. NumPy - Numerical calculations.
4. Matplotlib - Data visualisation. 
5. Seaborn - Statistical visualisation. 
6. Microsoft Excel - Dataset management and reporting. 
7. Google Colab - Python notebook environment.

## 5. Dataset Description

The project contains five connected synthetic datasets with a total of **9,600 records**.

  Dataset                     Records            Description 

  Customers                   1,000             Customer profiles and demographics. 
  Transactions                5,000             Purchase and transaction details.
  Products                    100               Product information and categories.
  Interactions                2,000             Customer interactions and satisfaction.
  Support_Tickets             1,500             Customer support and ticket details.

## Dataset Relationships

   Customer_ID connects customers with transactions, interactions, and support tickets.
   Product_ID connects transactions with product information.

The datasets include selected data-quality issues such as missing values, inconsistent text formatting, and transaction amount outliers for cleaning practice.

  ## 6. Project Workflow

The project is divided into eight phases.

Phase 1: Project Setup and Data Understanding
- Import Python libraries.
- Load all five datasets.
- Understand dataset structure, columns, and data types.

Phase 2: Data Exploration and Quality Checks
- Check missing values.
- Identify duplicate records.
- Inspect inconsistent values.
- Validate dataset relationships.

Phase 3: Data Cleaning and Preprocessing
- Handle missing values.
- Remove duplicate records where appropriate.
- Standardise text columns.
- Convert date columns.
- Detect transaction outliers.
- Validate foreign-key relationships.

Phase 4: Exploratory Data Analysis (EDA)
- Customer demographics analysis.
- Acquisition channel analysis.
- Monthly revenue analysis.
- Product and category performance.
- Customer spending analysis.
- Interaction and support analysis.

Phase 5: RFM Customer Segmentation

RFM stands for:

- **Recency:** How recently a customer purchased.
- **Frequency:** How frequently a customer purchased.
- **Monetary:** How much a customer spent.

Customers are grouped into segments such as:

- Champions
- Loyal Customers
- Potential Loyalists
- New Customers
- At Risk
- Hibernating
- Regular Customers

Phase 6: Customer Retention and Churn-Risk Analysis

- One-time and repeat customer analysis.
- Monthly active customer analysis.
- Cohort retention analysis.
- Customer inactivity calculation.
- Churn-risk categorisation.

Project-defined inactivity categories:

 Days Inactive         Category 

 0–30 Days             Active 
 31–60 Days            Low Risk 
 61–90 Days           Medium Risk 
 More than 90 Days    High Risk 

These categories indicate inactivity risk and do not confirm actual customer churn.

Phase 7: Customer Interaction and Support Analytics

- Interaction type analysis.
- Customer satisfaction analysis.
- Response time analysis.
- Support-ticket category analysis.
- Ticket priority and status analysis.
- Agent workload analysis.
- Ticket resolution time.
- SLA-style performance analysis.

The example resolution targets used are:
- High Priority: 1 day
- Medium Priority: 3 days
- Low Priority: 5 days

These are project assumptions, not actual company SLA commitments.

Phase 8: Python Dashboard and Data Visualisation

Create visualisations using Matplotlib and Seaborn.

Dashboard components include:
- Business KPI summaries
- Customer demographics
- Acquisition channel analysis
- Monthly revenue trends
- Product category performance
- RFM customer segmentation
- Customer retention analysis
- Churn-risk distribution
- Customer satisfaction
- Support-ticket performance
 
## 7. Key Analytical Techniques

- Data cleaning and preprocessing
- Missing-value treatment
- Duplicate detection
- Data transformation
- Data merging and aggregation
- GroupBy operations
- Date-based analysis
- IQR outlier detection
- RFM scoring
- Customer segmentation
- Cohort analysis
- Retention-rate calculation
- Correlation analysis
- Data visualisation
 
## 8. GitHub Repository Structure


Advanced-CRM-Customer-Analytics/

 ─ README.md

 ─ 01_Project_Dataset/
   - Advanced_CRM_Five_Datasets.xlsx

 ─ 02_Python_Notebook/
   ─ Advanced_CRM_Project.ipynb

 ─ 03_Analysis_Reports/
   ─ CRM_Cleaned_Datasets.xlsx
   ─ CRM_EDA_Analysis.xlsx
   ─ CRM_RFM_Analysis.xlsx
   ─ CRM_Retention_Churn_Analysis.xlsx
   ─ CRM_Customer_Support_Analysis.xlsx
   ─ CRM_Final_Dashboard_Data.xlsx

 ─ 04_Dashboard_Screenshots/
   ─ 01_KPI_Dashboard.png
   ─ 02_Monthly_Revenue.png
   ─ 03_Customer_Segmentation.png
   ─ 04_Cohort_Retention.png
   ─ 05_Churn_Analysis.png
   ─ 06_Customer_Support.png
 
 ─ 05_Project_Documentation/
   ─ CRM_Project_Report.pdf
