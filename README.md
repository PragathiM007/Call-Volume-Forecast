Call Volume Forecast Project
📌 Project Overview
This project aims to forecast daily call volumes for a call center by leveraging historical call data combined with reservation information and seasonal indicators. The goal is to build reliable time series models that capture how call volumes fluctuate over time and to understand the impact of reservations and special days on call center demand.

📊 Dataset

Sources:
case_data_calls.csv: Daily call volume data
case_data_reservations.csv: Reservation data with potential impact on call volumes
Time Period: January 1, 2013 to February 29, 2016 (3+ years of daily data)
Key Features:
Date (day-month-year format)
Calls received daily
Reservation counts (total and 2 months in advance)
Binary indicators for summer break, Christmas break, and special holidays
Weekday encoded as both integer and name
🎯 Objectives
Clean and preprocess time series and related features
Explore the relationships between call volumes, reservations, and seasonal patterns
Perform time series forecasting of call volumes
Evaluate model performance using metrics such as RMSE
Analyze the influence of holidays and special days on call demand
🧠 Models and Techniques Used
Linear Regression
Random Forest Regression
Train-test splitting with time-aware partitioning
Cross-validation to assess model stability
Hypothesis testing to evaluate operational impacts
📈 Performance Metrics
Root Mean Squared Error (RMSE) for model accuracy
Cross-validated RMSE to assess generalization
T-test statistics to measure significance of differences in abandonment rates
🔍 Key Findings
Linear regression slightly outperformed random forest in forecasting call volumes
Model performance varied significantly across different data folds, indicating possible seasonal or behavioral shifts
Statistical testing confirmed significant differences in abandonment rates linked to call volume variations
Reservations and holiday periods influence call demand, suggesting opportunities for improved staffing and resource planning
📊 Visualizations Included
Time series plots of call volume and reservation trends
Correlation heatmaps between key variables
Train-test split visualizations to ensure data integrity
Model prediction vs actual call volume comparisons
