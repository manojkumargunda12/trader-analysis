# trader-analysis
Data analysis of trader performance vs market sentiment (Fear/Greed) using Python, uncovering behavioral patterns and actionable trading insights.
# Trader Performance vs Market Sentiment Analysis

##  Objective
Analyze how market sentiment (Fear/Greed) influences trader behavior and performance.

##  Dataset
1. Bitcoin Fear/Greed Index
2. Hyperliquid Trader Data

##  Methodology
1. Data cleaning and preprocessing
2. Feature engineering (PnL, leverage, trade frequency)
3. Merging datasets by date
4. Segmentation analysis
5. Visualization and insights

##  Key Insights
1. Traders tend to have lower profitability during Fear periods due to risk aversion.
2. During Greed periods, traders increase leverage and trade frequency, leading to higher volatility.
3. High-leverage traders exhibit more extreme profit/loss swings compared to low-leverage traders.
      
##  Strategy Recommendations
1. Reduce leverage during Fear periods to minimize losses.
2. Limit overtrading during Greed phases to avoid emotional decision-making.

##  How to Run
```bash
pip install -r requirements.txt
jupyter notebook

## Results / Visualizations
1. PnL distribution across Fear vs Greed periods  
2. Leverage usage by sentiment  
3. Trade frequency comparison  

(Charts available in the notebook and /charts folder)

## Key Insights

1. Traders exhibit ~X% lower average PnL during Fear periods, indicating reduced profitability under risk-averse conditions.

2. Average leverage increases by ~Y% during Greed periods, suggesting higher risk-taking behavior.

3. High-leverage traders show significantly higher variance in returns, indicating increased exposure to extreme gains/losses.

##  Data Summary

1. Total trades: XXXX  
2. Unique traders: XXXX  
3. Date range: XXXX  
4. Missing values handled: Yes

##  Tools & Technologies

1. Python (Pandas, NumPy)
2. Matplotlib / Seaborn
3. Jupyter Notebook 
