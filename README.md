Trader Performance vs Market Sentiment Analysis

Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader behavior on the Hyperliquid trading platform. The objective is to determine whether market sentiment influences trader profitability, trading activity, and overall behavior, and to derive actionable trading recommendations.

Dataset:
1. Bitcoin Market Sentiment
Date
Fear & Greed Classification

2. Hyperliquid Historical Trader Data
Account
Symbol
Closed PnL
Position Size
Side
Timestamp
Order Details
Objectives
Clean and preprocess both datasets.
Merge sentiment and trading data by date.
Analyze trader performance across different market sentiment conditions.
Study changes in trading behavior.
Segment traders based on performance.
Recommend practical trading strategies.

Methodology:
Data Cleaning
Checked missing values
Removed duplicates
Converted timestamps
Merged datasets
Feature Engineering
Daily PnL
Win Rate
Average Trade Size
Trades per Day
Long/Short Ratio
Exploratory Data Analysis
Trader Segmentation
Strategy Recommendation

Key Insights:
Replace these with your actual findings. For example:
Traders achieved higher average profitability during Greed market conditions.
Trading activity increased during Fear periods.
Larger position sizes were associated with higher PnL volatility.
Long positions dominated during Greed periods.

Strategy Recommendations
Reduce position size during Fear and Extreme Fear periods to control downside risk.
Increase exposure only when positive market sentiment is supported by strong historical performance.

Technologies Used:
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
