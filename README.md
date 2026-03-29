# Trader Behavior Analysis under Market Sentiment (Fear vs Greed)

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

   
## Key Insights
1. Performance Difference: 

Traders incur an average loss of -23.7 during Fear conditions and achieve a significantly higher profit of +152.5 during Greed conditions.
This shows profitability is concentrated in favorable market conditions.

2. Behavioral Pattern: 

During Fear conditions, traders execute more BUY trades (74K), indicating “buy the dip” behavior.
During Greed conditions, traders execute more SELL trades (58K), indicating profit-taking.

3. Risk Behavior: 

Traders increase position sizes during profitable conditions, showing higher confidence and risk-taking.

## Strategy Recommendations
Avoid aggressive buying during Fear phases to prevent compounding losses
Apply structured profit-taking during Greed phases
Scale positions only during consistent profitability

## Results / Visualizations
1. PnL distribution across Fear vs Greed periods  
2. Leverage usage by sentiment  
3. Trade frequency comparison
   
##  Tools & Technologies

1. Python (Pandas, NumPy)
2. Matplotlib / Seaborn
3. Jupyter Notebook

## Conclusion

Trader performance and behavior are strongly influenced by market conditions.
Understanding sentiment-driven behavior can significantly improve risk management and trading outcomes.
