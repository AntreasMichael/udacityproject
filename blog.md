
# 🔍 What Drives Inflation?  
### Insights from 50 Years of Global Economic Data

Inflation touches every part of our lives — from grocery prices to interest rates, wages to government policy. But what really drives it? And more importantly, can we predict it?

To explore these questions, we analyzed nearly five decades of economic data from the **World Bank’s World Development Indicators**, focusing on key variables like foreign investment, GDP per capita, unemployment, and tax revenue. We also tested whether machine learning models could reliably forecast inflation based on these historical signals.

---

## ❓ Key Questions

- Which economic indicators are most strongly linked to inflation?
- Can a machine learning model accurately predict inflation using these inputs?
- What would happen in a hypothetical economy — can we simulate future inflation?

---

## 💡 What We Found

### 🔗 1. Some Indicators Move Together — Others Don’t

Our data exploration revealed clear patterns in how certain indicators relate to inflation:

| Economic Indicator                       | Correlation with Inflation |
|------------------------------------------|----------------------------|
| **Tax Revenue (% of GDP)**               | **+0.61**                  |
| **Unemployment Rate (%)**                | **+0.45**                  |
| **Foreign Direct Investment (% of GDP)** | **+0.32**                  |
| **GDP per Capita (US$)**                 | **–0.25**                  |

**Tax revenue** showed the strongest positive correlation with inflation. This could reflect policy responses to inflation (e.g., tax hikes), or the broader impact of government size on inflationary pressure.

Interestingly, **unemployment** had a moderately positive correlation — suggesting that in some economies, inflation and unemployment may rise together, potentially defying the traditional Phillips Curve.

---

### 🧠 2. Machine Learning Accurately Captures Inflation Trends

Using a supervised machine learning model (e.g., Random Forest Regression), we trained on historical data and achieved an **R² score of 0.93**, meaning the model explained over 90% of the variance in inflation.

This suggests that economic indicators like GDP, FDI, tax revenue, and unemployment contain enough signal to build predictive models — potentially useful for policy analysis or scenario planning.

---

### 🔮 3. Forecasting a Hypothetical Economy

We also used the model to simulate inflation for a fictional economy with the following profile:

| Indicator                        | Value            |
|----------------------------------|------------------|
| FDI (% of GDP)                   | 25%              |
| GDP per capita                   | $40,000          |
| Imports of goods/services        | $25 billion      |
| Tax revenue (% of GDP)           | 22%              |
| Unemployment rate                | 5%               |

➡️ **Predicted Inflation:** *3.19%*  

This scenario illustrates how governments, economists, or businesses might estimate inflation risks under specific economic conditions — without relying on guesswork.

---

## 🌍 Why It Matters

Inflation affects:

- 🛒 Everyday consumer purchasing power  
- 📉 Investment strategy and returns  
- 🏛️ Government budgets and interest rates  
- 🧮 Business pricing and planning  

By applying machine learning to large-scale economic datasets, we gain clearer visibility into the complex drivers of inflation — and the ability to forecast potential outcomes before they impact real-world decisions.

---

## 🙌 Acknowledgments

- **Data:** World Bank – World Development Indicators  
- **Tools Used:** Python, `pandas`, `scikit-learn`, `seaborn`, `matplotlib`

---

## 📌 See the Code

Interested in the full analysis? Check out the notebook, model training, and data cleaning process here:  


---

## ✨ Final Thoughts

Inflation is complex — driven by a web of domestic and global factors. But it's not entirely unpredictable. By combining historical data with modern tools, we can better understand where inflation is heading — and what to do about it.

Whether you’re an economist, data analyst, or just someone trying to make sense of rising prices, this kind of analysis provides a valuable edge.
