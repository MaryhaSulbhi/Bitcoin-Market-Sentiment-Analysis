# 📊 Trader Performance Analysis Using Bitcoin Market Sentiment

## 📌 Project Overview

This project analyzes the relationship between **Bitcoin market sentiment** and **trader performance** using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

The objective is to identify how different market sentiments (Extreme Fear, Fear, Neutral, Greed, and Extreme Greed) influence trading behavior, profitability, trade size, and overall trading activity.

---

## 📂 Datasets Used

### 1. Historical Trader Data
Contains detailed information about executed trades, including:
- Account
- Coin
- Execution Price
- Trade Size (USD)
- Side (BUY/SELL)
- Closed PnL
- Fee
- Timestamp

### 2. Bitcoin Fear & Greed Index
Contains daily Bitcoin market sentiment classified into:
- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

---

## 🎯 Project Objectives

- Analyze trader performance across different market sentiments.
- Compare average profitability under various sentiment conditions.
- Study trading activity during Fear and Greed markets.
- Examine BUY vs SELL behavior.
- Analyze trade size and transaction fees.
- Generate insights that can support smarter trading strategies.

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📈 Analysis Performed

The project includes the following analyses:

1. Number of Trades by Market Sentiment
2. Average Closed PnL by Market Sentiment
3. Closed PnL Distribution
4. Win Rate by Market Sentiment
5. Average Trade Size by Market Sentiment
6. BUY vs SELL Analysis
7. Overall Trade Distribution
8. Trading Fee Distribution
9. Top Traded Cryptocurrencies

---

## 📊 Key Findings

- Fear recorded the highest trading activity.
- Extreme Greed achieved the highest average profitability.
- Extreme Greed also had the highest win rate.
- Traders placed larger trades during Fear periods.
- SELL trades slightly exceeded BUY trades.
- Most trades incurred low transaction fees.
- Trading activity was concentrated among a few highly liquid cryptocurrencies.

---

## 💼 Business Recommendations

- Use market sentiment as a supporting indicator for trading decisions.
- Apply stronger risk management during Fear periods due to higher market volatility.
- Focus on highly liquid cryptocurrencies for improved trade execution.
- Combine sentiment analysis with technical indicators instead of relying solely on sentiment.

---

## 📁 Project Structure

```
Trader_Performance_Assignment/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── notebook/
│   └── Bitcoin_Sentiment_analysis.ipynb
│
├── images/
│   ├── trades_by_sentiment.png
│   ├── average_pnl_by_sentiment.png
│   ├── pnl_distribution_boxplot.png
│   ├── win_rate_by_sentiment.png
│   ├── average_trade_size.png
│   ├── buy_vs_sell_by_sentiment.png
│   ├── overall_buy_vs_sell.png
│   ├── fee_distribution.png
│   └── top15_traded_coins.png
│
├── report/
│   └── Final_Report.pdf
│
├── README.md
└── requirements.txt
```

---

## 🚀 Conclusion

This analysis demonstrates that Bitcoin market sentiment has a measurable impact on trader behavior and performance. Fear markets are associated with higher trading activity and larger trade sizes, while Extreme Greed shows higher average profitability and better win rates. Although sentiment alone cannot predict trading success, it provides valuable insights when combined with sound risk management and technical analysis.
