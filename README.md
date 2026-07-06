# 📊 Bitcoin Market Sentiment vs Trader Performance Analysis
## Need to download Historical_data which was not uploaded due to its size.
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
## 📌 Project Overview

This project analyzes the relationship between **Bitcoin Market Sentiment (Fear & Greed Index)** and **historical trader performance** on the Hyperliquid exchange.

The objective is to identify how market sentiment influences trading activity, profitability, and trader behavior by combining historical trading records with the Bitcoin Fear & Greed Index.

---

## 🎯 Objectives

- Clean and preprocess both datasets.
- Merge trader data with daily market sentiment.
- Perform Exploratory Data Analysis (EDA).
- Identify patterns between trader performance and market sentiment.
- Generate actionable insights that can support trading strategies.

---

## 📂 Dataset Information

### 1. Historical Trader Data

Contains trading records including:

- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Side (Buy/Sell)
- Timestamp
- Closed PnL
- Fees
- Trade ID
- Order ID

### 2. Bitcoin Fear & Greed Index

Contains daily market sentiment:

- Date
- Fear & Greed Value
- Classification
  - Extreme Fear
  - Fear
  - Neutral
  - Greed
  - Extreme Greed

---

## 🛠 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```
crypto_sentiment_analysis/
│
├── historical_data.csv
├── fear_greed.csv
├── Crypto_Trader_Sentiment_Analysis.ipynb
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone <repository-url>
```

Move into the project directory

```bash
cd crypto_sentiment_analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Crypto_Trader_Sentiment_Analysis.ipynb
```

and run all cells.

---

## 📈 Exploratory Data Analysis

The notebook includes the following analyses:

- Data Cleaning & Preprocessing
- Dataset Merging
- Missing Value Analysis
- Number of Trades by Market Sentiment
- Average Closed PnL by Sentiment
- Profit Distribution
- Win Rate Analysis
- Buy vs Sell Distribution
- Top Traded Coins
- Most Profitable Coins
- Trader-wise Performance Analysis
- Daily PnL Trend
- Correlation Analysis

---

# 📊 Key Findings

### Trading Activity

- Fear recorded the highest trading activity with **61,837 trades**.
- Greed accounted for **50,303 trades**.
- Extreme Greed accounted for **39,992 trades**.
- Neutral recorded **37,686 trades**.
- Extreme Fear had **21,400 trades**.

---

### Profitability

Average Closed PnL:

| Market Sentiment | Average Closed PnL |
|-----------------|-------------------:|
| Extreme Greed | 67.89 |
| Fear | 54.29 |
| Greed | 42.74 |
| Extreme Fear | 34.54 |
| Neutral | 34.31 |

Extreme Greed produced the highest average trader profitability.

---

### Win Rate

| Market Sentiment | Win Rate |
|-----------------|----------:|
| Extreme Greed | 46.49% |
| Fear | 42.08% |
| Neutral | 39.70% |
| Greed | 38.48% |
| Extreme Fear | 37.06% |

Extreme Greed achieved the highest trading win rate.

---

### Most Traded Coins

Top traded assets:

1. HYPE
2. @107
3. BTC
4. ETH
5. SOL

---

### Most Profitable Coins

Highest cumulative Closed PnL:

| Coin | Total Closed PnL |
|------|-----------------:|
| @107 | 2.78 Million |
| HYPE | 1.95 Million |
| SOL | 1.64 Million |
| ETH | 1.32 Million |
| BTC | 0.87 Million |

---

### Trader Performance

- Highest cumulative trader profit exceeded **2.14 Million**.
- Highest average profit per trade exceeded **520**.
- Highest observed trader win rate exceeded **81%**.

These results indicate significant variation in trader performance across accounts.

---

## 💡 Conclusion

This analysis demonstrates a clear relationship between market sentiment and trading performance.

Key observations include:

- Fear periods experienced the highest trading activity.
- Extreme Greed generated the highest average profits and win rates.
- HYPE and BTC dominated trading activity.
- @107 generated the highest cumulative profits.
- Trader performance varied significantly, with a small number of accounts contributing a large share of total profits.

These findings suggest that incorporating market sentiment indicators into trading strategies may improve decision-making and risk management.

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 👤 Author

**A Sai Anudeep Rao**

- Python Developer
- AI/ML Engineer
- Mathematics & Computing Graduate
