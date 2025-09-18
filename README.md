# udacityproject
Udacity 1st Project Repository for the Data Scientist course

# World Development Indicators: Economic Forecasting Project

## Project Motivation

This project analyzes economic indicators from the World Bank’s World Development Indicators dataset to understand how factors like foreign direct investment, GDP per capita, trade, tax revenue, and unemployment affect inflation. Using exploratory data analysis and machine learning, it aims to provide insights and predict inflation under hypothetical scenarios.

## Libraries Used

- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
- openpyxl  

Install dependencies with:  
```bash
pip install pandas matplotlib seaborn scikit-learn openpyxl

Summary of Analysis

Exploratory Data Analysis (EDA):
Found skewness in economic variables; strong correlation between GDP per capita and imports; unemployment shows some relation with inflation.

Data Cleaning:
Removed missing values and corrected year format.

Model Training:
Used RandomForestRegressor to predict inflation.
Model performance:

R² Score: ~0.93

Low RMSE, indicating accurate predictions.

Predictive Scenario:
For hypothetical values such as:

FDI: 25% of GDP

GDP per capita: $40,000

Imports: $25 billion

Tax revenue: 22% of GDP

Unemployment: 5%
The model predicts inflation of approximately X.X% (replace with your actual output).

Acknowledgments

World Bank for the data

scikit-learn, pandas, matplotlib, and seaborn for their tools

Future Work

Test additional models like XGBoost

Explore time series forecasting techniques

Develop interactive dashboards for predictions
