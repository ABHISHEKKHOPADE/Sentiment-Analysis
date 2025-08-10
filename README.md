# assignment
# 📊 Sentiment Trend Analysis on Crypto Trades

## 🔍 Overview
This project analyzes cryptocurrency trading data to identify **trader sentiment trends** and **market patterns**.  
The analysis focuses on correlating execution prices, trade directions, and PnL with market sentiment.

## 📂 Dataset
- Source: Hyperliquid Trading Data (sample)
- Key columns:
  - **Account** – Trader's wallet address
  - **Coin** – Cryptocurrency traded (e.g., BTC, DOGE, USTC)
  - **Execution Price** – Price at which trade was executed
  - **Size Tokens / USD** – Trade size in tokens and USD
  - **Side** – BUY or SELL
  - **Timestamp** – Trade date and time (IST)
  - **Direction** – Open Long / Close Short, etc.
  - **Closed PnL** – Profit or loss after closing the position

## ⚙️ Methodology
1. **Data Preprocessing**:
   - Parsed timestamps
   - Cleaned missing values
   - Normalized numeric features

2. **Exploratory Data Analysis (EDA)**:
   - Trade volume trends over time
   - Price movement patterns
   - PnL distribution per asset

3. **Sentiment Analysis**:
   - Positive sentiment → Profitable trades
   - Negative sentiment → Loss-making trades
   - Neutral sentiment → Small/no PnL

4. **Visualization**:
   - Sentiment distribution charts
   - Time-series trends for trade activity

## 📈 Key Insights
- Traders showed **bullish sentiment** during BTC rallies above $60k.
- Negative sentiment spikes coincided with sharp market drops.
- DOGE trades had the highest short-term profit volatility.

## 🛠 Tech Stack
- **Python** – pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook**
- **GitHub** for version control


