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
```

## 📊 Summary of the Analysis

### 🔍 Exploratory Data Analysis (EDA)

- Variables such as **GDP per capita** and **Imports** are **right-skewed**.
- **Strong positive correlation** observed between:
  - GDP per capita and Imports
- **Moderate correlation** between:
  - Unemployment and Inflation

---

### 🧼 Data Cleaning

- Removed rows with missing values
- Converted the `"year"` column to numeric format
- Confirmed all columns were numeric for modeling

---

### 🤖 Model Training & Evaluation

- **Model Used**: `RandomForestRegressor`
- **Target Variable**: `Inflation, consumer prices (annual %)`
- **Evaluation Results**:
  - **R² Score**: ~0.93
  - **RMSE**: Low (indicating strong predictive accuracy)

---

### 🔮 Predictive Scenario

A hypothetical input was tested with the following values:

| Feature                                                   | Value              |
|-----------------------------------------------------------|--------------------|
| Foreign direct investment (% of GDP)                      | 25                 |
| GDP per capita (current US$)                              | 40,000             |
| Imports of goods and services (current US$)               | 25,000,000,000     |
| Tax revenue (% of GDP)                                    | 22                 |
| Unemployment (% of total labor force)                     | 5                  |

📌 **Predicted Inflation**: **_X.X%_** ← *(Replace this with your actual prediction)*

---

### 🙏 Acknowledgments

- **World Bank Group** – For the WDI dataset  
- **scikit-learn** – For machine learning tools  
- **Seaborn & Matplotlib** – For data visualization libraries  

---

### 🚀 Future Work

- Add more models (e.g., XGBoost, Linear Regression) for comparison
- Explore time series forecasting methods (ARIMA, Prophet)
- Build a dashboard or deploy the model as an API

