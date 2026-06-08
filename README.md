# 📊 Trader Performance vs Market Sentiment Analysis

<img width="1878" height="1107" alt="image" src="https://github.com/user-attachments/assets/8e2a6488-dfbd-47ee-ac2a-d11fd732ae6d" />


---

## 🌟 Project Highlights

* 📈 Quantitative analysis of sentiment-driven trading behavior
* 🧠 Behavioral finance applied to crypto markets
* ⚡ Clean data pipeline + feature engineering
* 📊 Insight generation for strategy optimization

---

## 📌 Overview

This project evaluates the relationship between trader performance and market sentiment to identify patterns that support data-driven trading decisions.

It combines **trading data + sentiment indicators** to uncover how emotional market phases influence profitability, risk, and consistency.

---

## 🎯 Objective

* Assess the impact of market sentiment on:

  * Profitability (PnL)
  * Win Rate
  * Risk Behavior

* Identify behavioral trends across sentiment regimes

* Evaluate consistency of top-performing traders

---

## 📂 Dataset

### Trader Data

* Trade-level records including:

  * PnL (`closed_pnl`)
  * Position size (`size_usd`)
  * Account
  * Timestamp

### Sentiment Data

* Daily sentiment classification:

  * Extreme Fear → Extreme Greed

---

## ⚙️ Methodology

<img width="2048" height="1137" alt="image" src="https://github.com/user-attachments/assets/6162963c-9a14-40b2-8516-528de2d4b020" />


### Data Processing

* Standardized column names
* Converted timestamps to datetime
* Cleaned missing values

### Feature Engineering

* Risk proxy: normalized position size
* Win indicator: PnL > 0
* Sentiment encoded on ordinal scale (0–4)

### Data Integration

* Merged datasets on date

---

## 📈 Analysis

<img width="349" height="437" alt="image" src="https://github.com/user-attachments/assets/a4348530-7daa-41aa-94d6-32e5f88c41e4" />


* Profitability by sentiment
* Win rate by sentiment
* Risk behavior across sentiment phases
* Trader-level performance aggregation
* Time-series PnL trend
* Correlation analysis

---

## 📊 Key Results

<img width="1536" height="850" alt="image" src="https://github.com/user-attachments/assets/ca7bd287-3030-41d5-be0d-839bf99aee89" />


* Greed Avg PnL: **+$540**

* Fear Avg PnL: **-$310**

* **~2.7× performance difference**

* Higher win rates observed in bullish sentiment

* Risk exposure increases with positive sentiment

* Conservative positioning during fear phases

---

## 📉 Visual Insights

<img width="671" height="672" alt="image" src="https://github.com/user-attachments/assets/36dbb1fa-2e15-417b-bc67-6df4401146db" />


👉 See full analysis in presentation:
**📎 trader_sentiment_analysis.pptx**

👉 Research paper included:
**📄 Market Sentiment Study (PDF)**

---

## 🧠 Strategic Insights

* Market sentiment provides contextual trading signals
* Profitability is highest during Greed phases
* Risk increases alongside returns
* Emotionally disciplined traders outperform
* Sentiment alone is insufficient without risk control

---

## ⚠️ Limitations

* Daily sentiment may miss intraday dynamics
* Risk proxy does not capture leverage
* External factors (news, macro events) not included
* Limited dataset scope

---

## 🔮 Future Improvements

* Intraday sentiment integration
* Advanced risk metrics (drawdown, leverage)
* Machine learning for trade prediction
* Multi-exchange and longer time horizon data
* Integration of macroeconomic & news sentiment

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📁 Project Structure

```
├── data/
├── notebooks/
├── analysis.py
├── trader_sentiment_analysis.pptx
├── research_paper.pdf
└── README.md
```

---

## 🚀 Execution

```bash
pip install pandas numpy matplotlib seaborn
```

```bash
python analysis.py
```

---

## 🧪 Research Contribution

This project contributes to **behavioral finance in cryptocurrency markets** by:

* Quantifying sentiment-performance relationships
* Demonstrating risk-return trade-offs
* Providing a foundation for predictive modeling

---

## 📌 Notes

This project emphasizes:

* Structured analytical workflow
* Clarity and simplicity
* Data-driven decision making
* Continuous improvement mindset (**Kaizen philosophy**)

---

## 👤 Author

**Satyam Singh Patel**
🔗 https://github.com/satyamsinghpatel476

---
