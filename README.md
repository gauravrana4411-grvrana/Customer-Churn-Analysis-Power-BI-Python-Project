# Customer-Churn-Analysis-Power-BI-Python-Project
Customer Churn Analysis using Power BI and Python: data cleaning, feature engineering, and EDA with Python, plus interactive dashboards in Power BI to identify churn drivers, segment customers, and support data-driven retention strategies.

Overview

This project analyzes customer churn behavior using Power BI Desktop integrated with Python scripting. The goal is to identify key drivers of churn and provide actionable insights through interactive dashboards and advanced visual analytics.

Situation

A telecommunications company was experiencing high customer churn and needed a data-driven approach to understand:

Why customers were leaving

Which customer segments were at higher risk

How pricing, contracts, and tenure impacted churn

The available dataset required data cleaning, transformation, and feature engineering before meaningful analysis could be performed.

Task

Clean and preprocess the Telco customer dataset

Engineer new features to improve churn analysis

Perform exploratory data analysis using Python

Build interactive and insightful dashboards in Power BI

Present churn drivers clearly for business decision-making

Action
Data Loading & Cleaning (Python in Power BI)

Loaded the dataset using Python Script inside Power BI

Handled missing values and removed invalid records

Converted TotalCharges to numeric format for accurate calculations

Data Transformation & Feature Engineering

Transformed Yes/No values into binary (1/0) for analysis

Created a new feature MonthlySpendGroup using quartile-based segmentation

Categorized customers based on spending behavior

Exploratory Data Analysis (Python Visuals)

Violin Plot: Compared Monthly Charges distribution by churn status

Correlation Heatmap: Identified relationships between numerical variables

Histogram by Contract: Analyzed tenure distribution across contract types

Power BI Dashboards

Created three interactive dashboards:

Customer Churn – Executive Overview

Customer Churn – Behavioral & Service Analysis

Customer Churn – Contract & Tenure Insights

Each dashboard includes KPIs, filters, and visuals to explore churn trends dynamically.

Results

Identified higher churn among month-to-month contract customers

Found that higher monthly charges correlate with increased churn

Discovered longer tenure significantly reduces churn probability

Enabled stakeholders to segment customers by spend level and risk

Delivered a decision-ready dashboard for churn reduction strategies

Tools & Technologies

Power BI Desktop

Python (Pandas, Seaborn, Matplotlib)

Power Query with Python integration

DAX for measures & KPIs
