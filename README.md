# Mini-Project-On-Backtested-Swing-Call-Strategies
Mini-project: Backtested Swing Call Strategies using EMA Algorithms with Sentiment Analysis (Python, Google Colab)
# 📊 Backtested Swing Call Strategies using EMA Algorithms

**Mini-Project** — Bachelor of Technology in Computer Science  
**Submitted by**:  
- Pooja Sawant (58)  
- Chandraprabha Tawade (64)  
- Sakshi Tripathi (65)  
**Guide**: Prof. Sonal Kadam  
**Usha Mittal Institute of Technology, S.N.D.T. Women’s University, Mumbai**  
📅 Jan–Apr 2025

---

## 📜 Overview
This project explores **Exponential Moving Average (EMA)-based swing trading strategies** combined with **sentiment analysis** to improve stock trading decisions.

Key objectives:
- 🧠 Develop data-driven buy/sell signals using 20- & 50-day EMAs
- 📰 Integrate **VADER-based sentiment analysis** on financial news
- 📊 Backtest the strategy on historical data to evaluate performance

---

## 🎯 Features
- ✅ Fetch historical stock data via `yfinance`
- ✅ Implement 20- and 50-day EMA crossover trading signals
- ✅ Parse financial news using `feedparser`
- ✅ Assess news with VADER sentiment analysis (`nltk`)
- ✅ Simulate trades & generate key metrics:
  - Return on investment
  - Win/loss ratio
  - Sharpe Ratio & drawdown
- ✅ Visualize:
  - Candlestick charts with EMAs & buy/sell markers
  - Sentiment distributions
  - Portfolio equity curve vs. benchmark index

---

## 🧠 Methodology
1. **Data Collection** — Fetch price & news data
2. **Preprocessing** — Clean & structure the data
3. **Signal Generation** — Compute 20- & 50-day EMAs; detect crossovers
4. **Sentiment Analysis** — Assess headlines with VADER
5. **Backtesting** — Simulate historical trades
6. **Result Analysis** — Summarize performance, visualize trends

---

## 🛠️ Tech Stack
| Language & Tools | Description |
|------------------|-------------|
| **Python 3.x** | Core language |
| `numpy`, `pandas` | Data handling |
| `matplotlib`, `mplfinance` | Charts & visualization |
| `yfinance` | Historical price data |
| `feedparser` | Fetch RSS news feeds |
| `nltk` (VADER) | Sentiment analysis |
| `fpdf` | PDF report generation |

---

## 📂 Repository Contents
| File | Description |
|------------|------------|
| `code.ipynb` | Implementation in Colab/Jupyter |
| `report.pdf` | Detailed mini-project report |
| `presentation.pdf` | Slides used for presentation |
| `images/` | Charts, diagrams & screenshots |

---

## 📊 Future Scope
- ⚡ Integrating real-time trading with broker APIs (e.g. Zerodha, Upstox)
- 🤖 Adding more advanced technical indicators (MACD, RSI, Bollinger Bands)
- 🧠 Using machine learning to optimize EMA lengths
- 🐦 Including social media sentiment (Twitter/Reddit)

---

## 🎓 Conclusion
This mini-project successfully combines technical & sentiment analysis to create a **robust, data-driven swing trading framework**. Backtesting and performance evaluation demonstrate the strategy’s practicality and set the stage for future enhancements.

---

## 👥 Authors
**Pooja Sawant | Chandraprabha Tawade | Sakshi Tripathi**  
**Guide**: Prof. Sonal Kadam  
**Usha Mittal Institute of Technology, SNDT Women’s University**  
2024–2025
