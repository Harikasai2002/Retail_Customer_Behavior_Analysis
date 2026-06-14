Retail Customer Behavior Analysis

Project Overview
This project focuses on analyzing retail customer shopping behavior to extract meaningful insights that support business decision-making. The dataset is processed using Python, stored and analyzed using PostgreSQL, and visualized through an interactive Power BI dashboard.

The goal is to understand customer purchasing patterns, identify key influencing factors, and generate actionable insights for improving marketing strategies, customer retention, and revenue optimization.

Objectives
Analyze customer purchasing behavior
Identify factors influencing buying decisions
Perform customer segmentation
Analyze the impact of discounts and subscriptions
Generate business insights for decision-making

Dataset Information
Source: Kaggle (Customer Shopping Behavior Dataset)
Records: ~3900 entries
Type: Secondary dataset
Key Features:
Customer ID
Age & Gender
Product Category
Purchase Amount
Review Rating
Discount Applied
Payment Method
Frequency of Purchases
Subscription Status

Tools & Technologies Used
Python (Pandas, NumPy) – Data Cleaning & Feature Engineering
PostgreSQL – Data Storage & SQL Analysis
SQL – Business Queries & Insights
Power BI – Dashboard & Data Visualization
Jupyter Notebook – Development Environment

Project Workflow
Data Collection (CSV dataset from Kaggle)
Data Cleaning & Preprocessing using Python
Feature Engineering (Age Group, Purchase Frequency Conversion)
Data Integration into PostgreSQL
SQL-based Business Analysis
Power BI Dashboard Development
Insight Generation & Interpretation

Data Preprocessing Steps
Handled missing values in Review Rating using category-wise median
Standardized column names using snake_case format
Converted categorical frequency data into numerical values
Created new features:
Age Group (Young Adult, Adult, Middle-aged, Senior)
Purchase Frequency (converted to days)
Removed redundant column (promo_code_used)

Feature Engineering
Age Group Segmentation for behavioral analysis
Purchase Frequency Conversion for numerical analysis
Improved dataset usability for SQL and BI tools

Database Integration
Connected Python to PostgreSQL using SQLAlchemy
Loaded cleaned dataset into database table customer
Enabled structured querying for business analysis

SQL Analysis Performed

Key business questions answered:

Revenue comparison by gender
Impact of discounts on spending behavior
Top-rated products
Subscription vs non-subscription analysis
Customer segmentation (New, Returning, Loyal)
Age group revenue contribution
Product popularity ranking

Power BI Dashboard

The interactive dashboard includes:

Total Revenue KPI
Customer segmentation charts
Age-wise analysis
Product performance
Discount impact visualization
Subscription analysis

Key Insights
Customer behavior varies significantly across age groups
Discounts influence purchasing decisions
Loyal customers contribute higher revenue
Subscription users show higher engagement
Certain products perform consistently well regardless of discounts

Business Impact

This project helps businesses to:

Improve targeted marketing strategies
Optimize discount campaigns
Enhance customer retention programs
Identify high-value customer segments
Improve inventory and product planning

Future Scope
Predictive modeling using Machine Learning
Customer churn prediction
Recommendation systems
Real-time analytics dashboard

Conclusion

This project demonstrates an end-to-end data analytics pipeline using Python, SQL, and Power BI. It transforms raw retail data into meaningful business insights that can support strategic decision-making in the retail industry.


Author

Harika
M.Sc Data Science

References
Kaggle Dataset
Python Documentation
PostgreSQL Documentation
Power BI Documentation
Pandas & NumPy Libraries
