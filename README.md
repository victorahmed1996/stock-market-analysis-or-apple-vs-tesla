# 📊 Project: Analyzing Stock Market Trends — Apple vs Tesla

## 👋 Introduction
In this project, I explored historical stock price data of Apple (AAPL) and Tesla (TSLA) to compare their trends, volatility, and returns. This analysis can help investors understand market behavior and assess risk over time.

## 📁 Dataset
- Source: [Yahoo Finance via yfinance Python library](https://pypi.org/project/yfinance/)
- Data Range: January 2018 – December 2023
- Features: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`

## 🧹 Step 1: Data Collection
- Used the `yfinance` library in Python to download daily historical prices.
- Focused on adjusted closing prices to account for stock splits/dividends.

## 🧼 Step 2: Data Cleaning
- Checked for missing values and duplicates
- Reset index and formatted `Date` column

## 📊 Step 3: Analysis Performed
- Line chart of stock price trends over time
- Calculated daily returns for each stock
- Compared volatility (standard deviation of daily returns)
- Correlation between AAPL and TSLA

## 📈 Step 4: Visualization
- Price trends: AAPL vs TSLA
- Histogram of daily returns
- Rolling average comparison
- Scatter plot for correlation

## 💡 Key Insights
- Tesla stock is significantly more volatile than Apple.
- Apple showed steady growth with fewer extreme changes.
- There is a moderate positive correlation between the two stocks.

## 🧰 Tools Used
- Python
- Pandas, Matplotlib, Seaborn
- yfinance
- Google Colab
