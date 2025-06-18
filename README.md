# ML for Trading Strategies 📈

This repository is a collection of machine learning-based models and strategies developed for algorithmic trading. These projects were created **purely for learning and experimentation purposes**, with a focus on feature engineering, model building, and backtesting using financial market data.

## 🧠 Project Overview


### `limit_order_book_regression/`
This project was developed as part of the [Taramani Quant Research Contest (TQRC)](https://www.kaggle.com/competitions/taramani-quant-research-contest-tqrc/overview).

**Goal:** Predict short-term future returns using Limit Order Book (LOB) data.

- Focuses on **predicting short-term future returns** from Limit Order Book (LOB) data.
- Uses hand-crafted features (volume imbalance, order flow, spreads, liquidity, etc.).
- Applies **linear regression** to predict returns from these curated features.
- Outputs predictions in the required submission format for the contest.

### `Pfizer/`
A separate project focused on creating a single-asset machine learning trading strategy on **Pfizer (PFE)** stock using OHLCV data.

**Strategy Constraints:**
- Each day, take one position: **Long or Short** $1 million worth of PFE.
- No hold or neutral positions allowed.
- Focus on **outperforming a long-only baseline** on out-of-sample data.

Trained ML model using Logistic Regression to predict buy-sell signals.
## 🛠 Tools & Libraries
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualization)
- Backtesting utilities (custom or built-in)

## ⚠️ Disclaimer
This repository is intended for **educational and research purposes only**. The models and strategies developed are **not suitable for live trading** without further robustness checks, risk management, and regulatory compliance.

---




