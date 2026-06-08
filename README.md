# 📊 Trader Performance vs Market Sentiment Analysis



## 📌 Overview

This project evaluates the relationship between trader performance and market sentiment to identify patterns that support data-driven trading decisions.



---



## 🎯 Objective

- Assess the impact of market sentiment on:

  - Profitability (PnL)

  - Win Rate

  - Risk Behavior  

- Identify behavioral trends across sentiment regimes  

- Evaluate consistency of top-performing traders  



---



## 📂 Dataset



### Trader Data

- Trade-level records including:

  - PnL (closed_pnl)

  - Position size (size_usd)

  - Account

  - Timestamp  



### Sentiment Data

- Daily sentiment classification:

  - Extreme Fear → Extreme Greed  



---



## ⚙️ Methodology



### Data Processing

- Standardized column names  

- Converted timestamps to datetime  

- Cleaned missing values  



### Feature Engineering

- Risk proxy: normalized position size  

- Win indicator: PnL > 0  

- Sentiment encoded on ordinal scale (0–4)  



### Data Integration

- Merged datasets on date  



---



## 📈 Analysis



- Profitability by sentiment  

- Win rate by sentiment  

- Risk behavior across sentiment phases  

- Trader-level performance aggregation  

- Time-series PnL trend  

- Correlation analysis  



---



## 📊 Key Findings



- Profitability increases during Greed phases  

- Win rates are higher in positive sentiment conditions  

- Risk exposure rises during bullish markets  

- Conservative behavior observed during Fear phases  

- Top traders maintain stable performance across sentiments  



---



## 🧠 Strategic Insights



- Market sentiment provides contextual trading signals  

- Risk management is critical for consistent performance  

- Sentiment alone is insufficient without disciplined execution  



---



## ⚠️ Limitations



- Sentiment data is aggregated daily and may not reflect intraday market changes  

- Risk proxy is based on position size and does not represent actual leverage  

- External factors such as news, macroeconomic events, and volatility are not included  

- Data scope may be limited in duration and diversity of market conditions  



---



## 🔮 Future Improvements



- Incorporate intraday sentiment data to improve timing accuracy  

- Include market volatility indicators (e.g., VIX, volume spikes)  

- Enhance risk measurement using leverage and drawdown metrics  

- Apply machine learning models for predictive analysis  

- Expand dataset across longer time periods and different market regimes  

- Integrate external data sources such as news and macroeconomic indicators  



---



## 🛠️ Tech Stack

- Python  

- Pandas  

- NumPy  

- Matplotlib  

- Seaborn  



---



## 🚀 Execution



```

pip install pandas numpy matplotlib seaborn

```



```

python analysis.py  

```

---



## Notes

This project emphasizes:

- Structured analytical workflow  

- Clarity and simplicity  

- Data-driven decision support  

- Continuous improvement mindset (Kaizen)  



---



## 👤 Author

Satyam Singh Patel  

https://github.com/satyamsinghpatel476  
