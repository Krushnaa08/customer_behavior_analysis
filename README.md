Customer Shopping Behavior Analysis
Overview

This project analyzes customer shopping behavior data to identify purchasing trends, customer segments, and business opportunities for a retail company. The objective is to transform raw customer transaction data into actionable insights that support marketing, product, and customer engagement decisions.

The workflow includes data cleaning in Python, business analysis using SQL, dashboard creation in Power BI, reporting, and presentation development.

Project scope came from the business case in your provided documentation.

Dataset

The dataset contains customer shopping transactions and behavioral information collected from retail purchases.

Dataset Summary
Records: 3,900 customer transactions
Features: 18 columns
Includes:
Customer demographics
Product purchase details
Shopping behavior
Subscription details
Ratings and purchase frequency

Main attributes include age, gender, location, item purchased, category, purchase amount, season, shipping type, discount status, and previous purchases.

----Tools Used
*Python
*Pandas

*SQL
*MySQL Server
*MySQL Workbench
Visualization
*Power BI
*Documentation
*PDF Report
*Gamma (Presentation)
-----------*Project Steps
1. Data Loading
Imported CSV dataset using Python
Loaded data into pandas DataFrame
Inspected dataset structure and basic statistics
2. Exploratory Data Analysis (EDA)
Checked:
Data types
Missing values
Duplicate rows
Summary statistics
Distribution patterns
3. Data Cleaning
Handled missing values
Standardized column names
Converted columns into analysis-friendly format
Created new derived columns for better segmentation
Removed redundant fields
4. SQL Analysis

Cleaned data was imported into MySQL for business query analysis.

SQL analysis included:

Revenue by gender
Subscription behavior
Customer segmentation
Product performance
Discount impact
Purchase trends
Age-group revenue
Repeat customer analysis

These business questions align with the analysis described in your report.

Dashboard

Power BI dashboard was created to visualize key insights interactively.

Dashboard Highlights
Total sales overview
Customer segmentation
Product category trends
Subscription comparison
Purchase frequency
Discount analysis
Revenue by age group
Shipping type trends

Files included:

customer_behavior_dashboard.pbix
Project Structure
customer-shopping-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── analysis.ipynb / python scripts
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── report/
│   └── Customer Shopping Behavior Analysis.pdf
│
├── presentation/
│   └── Gamma PPT export
│
└── README.md
Results

Key findings from the analysis:

Customer spending differs across demographic groups
Subscription users show stronger long-term engagement
Discounts influence purchasing behavior significantly
Certain products perform consistently across seasons
Loyal customers generate a larger share of revenue
Review ratings impact product preference
Shipping preferences affect average spending

Recommendations in your report emphasize loyalty programs, subscription growth, and targeted campaigns.

How to Run
Python Analysis
Install dependencies
pip install pandas numpy matplotlib seaborn mysql-connector-python
Run notebook or script
python analysis.py
SQL
Open MySQL Server
Import cleaned dataset
Execute queries from:
customer_behavior_sql_queries.sql
Power BI
Open:
customer_behavior_dashboard.pbix
Refresh dataset if required
Business Objective

The project answers the business question:

How can customer shopping data be used to identify trends, improve customer engagement, and optimize marketing strategies?

This was the core business problem defined in the assignment document.

Author

Krushna Salunkhe
Data Analytics Project
Python • SQL • Power BI • Business Analysis
