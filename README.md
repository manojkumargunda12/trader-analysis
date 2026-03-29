# trader-analysis
Data analysis of trader performance vs market sentiment (Fear/Greed) using Python, uncovering behavioral patterns and actionable trading insights.
# Trader Performance vs Market Sentiment Analysis

## 📌 Objective
Analyze how market sentiment (Fear/Greed) influences trader behavior and performance.

## 📊 Dataset
- Bitcoin Fear/Greed Index
- Hyperliquid Trader Data

## ⚙️ Methodology
- Data cleaning and preprocessing
- Feature engineering (PnL, leverage, trade frequency)
- Merging datasets by date
- Segmentation analysis
- Visualization and insights

## 🔍 Key Insights
1. Traders tend to have lower profitability during Fear periods due to risk aversion.
2. During Greed periods, traders increase leverage and trade frequency, leading to higher volatility.
3. High-leverage traders exhibit more extreme profit/loss swings compared to low-leverage traders.

## 💡 Strategy Recommendations
- Reduce leverage during Fear periods to minimize losses.
- Limit overtrading during Greed phases to avoid emotional decision-making.

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook
