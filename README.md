# 📊 Correlation-Weighted Network Analysis of Stock Prices

This project performs a **correlation-weighted network analysis** on daily closing prices of major U.S. stocks to uncover relationships, clusters, and dependencies in the financial market.  
This work is completed as part of **IE6400 – Foundations for Data Analytics Engineering (Fall 2025)**.

---

## 📌 Project Objective

The objective of this project is to construct and analyze a **correlation-based stock network**, where:
- Each node represents a stock
- Each edge represents a strong correlation between stock prices
- Edge weights reflect the strength of the correlation

This network provides insights into market structure and diversification opportunities.

---

## 📂 Dataset Description

- **Source:** Yahoo Finance (`yfinance`)
- **Time Period:** January 1, 2020 – December 31, 2020
- **Stocks:** 20 major U.S. companies across technology, finance, healthcare, retail, and consumer sectors

### Tickers
AAPL, MSFT, GOOGL, AMZN, META, TSLA, NVDA, BRK-B, JNJ, V, WMT, JPM, UNH, MA, PG, HD, DIS, ADBE, NFLX, PYPL

---

## 🧪 Methodology

1. Data collection using `yfinance`
2. Data cleaning and alignment
3. Pearson correlation matrix computation
4. Threshold-based network construction
5. Network visualization using NetworkX
6. Interpretation of clusters and relationships

---

## 📈 Key Insights

- Technology stocks form strong correlation clusters
- Financial stocks show close interconnections
- Highly connected nodes indicate systemic market behavior
- Network structure supports portfolio diversification decisions

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- NetworkX
- Matplotlib
- yFinance

