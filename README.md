# Pharma-Sales-Analytics-Dashboard
Pharma Sales Analytics Dashboard built using Python, SQL, Excel, and Power BI to analyze multi-level pharmaceutical sales data, identify demand trends, perform statistical analysis, and create interactive business intelligence dashboards for data-driven decision making.

Pharma Sales Analytics & Demand Forecasting

Project Overview

This project focuses on analyzing pharmaceutical sales data to understand demand patterns, sales trends, and key business drivers. The goal is to help a pharma company make data-driven decisions related to inventory planning, demand forecasting, and sales strategy.
The project covers the complete data analytics lifecycle, including data exploration, SQL analysis, statistical reasoning, probability analysis, and machine learning–based forecasting.

Business Problem

Pharmaceutical companies need to:
Identify high-demand drug categories
Understand seasonal and time-based sales patterns
Compare weekday vs weekend demand
Forecast future demand to avoid stock-outs or over-stocking
This project answers these questions using historical sales data.

 Dataset Description

The analysis uses multi-granularity sales data:
salesdaily.csv – Daily drug sales data
saleshourly.csv – Hour-wise sales data
salesweekly.csv – Weekly aggregated sales
salesmonthly.csv – Monthly aggregated sales
Using multiple datasets allows analysis at different time levels and avoids noise during forecasting.

Tools & Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)
SQL (MySQL) – business queries & analytics
Excel – pivot analysis & KPI reporting
Statistics & Probability – hypothesis testing, risk analysis
Machine Learning
Regression models
Time-series forecasting (Prophet)
Google Colab – development environment

Exploratory Data Analysis (EDA)

Key EDA steps included:
Data quality checks and validation
Trend analysis (daily, monthly, yearly)
Seasonality and peak demand identification
Outlier and variability analysis
Drug-wise contribution analysis
Hourly, weekday, and weekend demand patterns

 Statistical & Probability Analysis

Distribution analysis of drug demand
Hypothesis testing (weekday vs weekend sales)
Correlation analysis between drug categories
Probability of high-demand events
Conditional probability for weekend and peak-hour demand
These analyses help in understanding uncertainty and demand risk.

Machine Learning & Forecasting

Regression model to predict drug sales using time-based features
Time-series forecasting to predict future demand for high-selling drugs
Model evaluation using error metrics and trend validation

 SQL Analysis

SQL was used to extract business insights such as:
Total and average sales per drug
Yearly and monthly sales trends
Peak sales days and hours
Weekend vs weekday comparison
Running totals, ranking, and growth analysis using window functions

Excel Analysis

Excel was used for:
Pivot-based analysis
KPI calculations
Quick business summaries
Stakeholder-friendly reporting

Key Insights

N02BE is the highest-demand drug category
Sales show clear seasonal and monthly patterns
Demand varies significantly by hour and weekday
Weekend demand differs from weekdays
Forecasting indicates periods of increased future demand

 Business Recommendations

Increase inventory during peak demand months
Optimize staffing and supply during high-demand hours
Focus sales strategy on high-growth drug categories
Use forecasting results for proactive inventory planning

Project Structure

Pharma-Sales-Analytics
│
├── data
├── notebooks
├── sql
├── excel
├── dashboards
├── presentation
├── images
└── README.md

Conclusion

This project demonstrates an end-to-end data analytics workflow combining EDA, SQL, statistics, probability, machine learning, and business storytelling. It reflects real-world analytics tasks commonly performed in consulting and analytics-driven organizations.
