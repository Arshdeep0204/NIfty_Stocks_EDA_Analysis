# Nifty_Stocks EDA & Risk Analysis

## Project Overview

This project performs an Exploratory Data Analysis (EDA) and risk assessment on 5 NIFTY stocks over a 3-year period.  
The goal is to understand stock performance, volatility behavior, correlations, and diversification opportunities based on daily return patterns.

Stocks Analyzed:
- **TCS**
- **RELIANCE**
- **HDFCBANK**
- **SBIN**
- **ICICIBANK**

---

## Step 1 — Importing Dependencies

Used the following Python libraries:
- pandas, numpy
- yfinance
- matplotlib, seaborn
- datetime

---

## Step 2 — Defining Ticker List & Date Range

- Collected historical price data for the 5 selected stocks  
- Used 3 years (1096 days) of historical data  
- Defined tickers and automated date range using Python’s datetime module  

---

## Step 3 — Data Download & Preparation

- Downloaded closing prices using `yfinance.download()`  
- Extracted the `Close` column into a new dataframe  
- Checked for missing values  
- Calculated **daily percentage returns** for each stock  
- Cleaned data using `.dropna()`  

---

## Step 4 — Summary Statistics

Generated descriptive statistics for:
- **Closing Prices** (mean, std, min, max, quartiles)
- **Daily Returns** (mean return, volatility, distribution spread)

Also calculated:
- **Skewness** (asymmetry of returns)
- **Kurtosis** (fat-tailed behavior)

These metrics help understand return behavior and risk characteristics.

---

## Step 5 — Data Visualization

### 1️⃣ Daily Return Histograms  
Analyzed distribution shape, volatility, and return dispersions.

### 2️⃣ Box Plots (Daily Returns)  
Compared medians, outliers, and return variability between stocks.

### 3️⃣ Risk vs. Return Scatter Plot  
Visualized:
- **Annualized Return**
- **Annualized Volatility**

Used to identify best-performing and most stable stocks.

### 4️⃣ Correlation Heatmap  
Displayed correlation between stock returns to highlight:
- Highly correlated pairs (move together)
- Low correlated pairs (good for diversification)

### 5️⃣ Rolling 30-Day Annualized Volatility  
Observed how volatility evolved over time for each stock.

---

## Step 6 — Answering Key Questions

### ✅ 1. Which stock delivered the highest annualized return?
**SBIN** delivered the highest annualized return (~21.37%).

### ✅ 2. Which stock showed the lowest annualized volatility?
**ICICIBANK** had the lowest volatility (~17.69%) — most stable.

### ✅ 3. Which stocks had the highest peak rolling volatility?
Top 3:
1. SBIN  
2. RELIANCE  
3. ICICIBANK  

### ✅ 4. Which stock pairs are most / least correlated?
- **Most correlated pair:** SBIN & ICICIBANK  
- **Least correlated pair (best for diversification):** HDFCBANK & TCS  

---

## Insights & Conclusion

- **SBIN** offers the strongest performance but with higher volatility.  
- **ICICIBANK** emerges as the most stable stock.  
- Correlation analysis helps identify diversification-friendly stock combinations.  
- Rolling volatility reveals how market risk changes dynamically.  
- Using EDA + visualizations provides clearer insight into stock behavior than raw prices alone.

This analysis showcases strong command over Python, financial data interpretation, and analytical visualization techniques.

---

## Project Files

- `Stock_EDA_Analysis.ipynb` — Full notebook with all analysis   

---

## Continuous Learning

This project strengthened my understanding of:
- Financial data analysis  
- Return & risk metrics  
- Market behavior interpretation  
- Python visualization frameworks  
- Quantitative analysis techniques  

---

## Contact

If you'd like to discuss analytics, finance, or Python, feel free to connect!

LinkedIn: **https://www.linkedin.com/in/arshdeep-singh-7a4043196**

