# Predicting Regency Centers' Expenses Using Machine Learning

# Introduction
This project aims to apply advanced machine learning techniques to predict the expenses of Regency Centers. Leveraging a comprehensive dataset, the project seeks to uncover the factors that significantly impact operational costs.

# Objective
The primary objective is to develop predictive models that can accurately forecast the expenses of Regency Centers based on various criteria, including historical expenditure data, geographical factors, and external economic indicators like petrol prices.

# Data Source
The analysis is based on data provided by the Regency Centers, encompassing detailed records of previous expenses, categorized by type, along with information about the centers' locations (zipcodes), sizes, and other relevant attributes.

# Analysis Overview
- Previous Expenses and Their Categorization: Examining historical expense data to identify trends and categorize spending patterns.
- Zipcode and Size of Regency Centers: Analyzing how location and the physical size of the centers influence their operational costs.
- Proximity to Water Surfaces: Investigating if being near water bodies affects expenses, possibly due to environmental regulations or insurance costs.
- Impact of Petrol Prices: Assessing how fluctuations in petrol prices correlate with the overall expenses of the centers.
- Time series analysis, seasonality, and trend analysis for each of the expenses.

Machine Learning Models Used
A range of machine learning models have been employed to predict the expenses. These include:

- Linear Regression Models: For establishing baseline predictions and understanding linear relationships between variables.
- Random Forests: To capture non-linear patterns and interactions between different expense factors.
- GradientBoostingRegressor
  
Each model's performance was evaluated based on accuracy and ability to generalize, using TimeSeriesSplit.

# Results and Insights
The models have yielded insightful findings. For instance, the proximity to water surfaces had an impact on certain expense categories, likely due to additional environmental compliance costs. Similarly, petrol prices showed a correlation with transport-related expenses. These insights can guide cost optimization strategies and informed decision-making for Regency Centers.
