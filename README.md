# 📊 Trader Performance vs Market Sentiment Analysis

<p align="center">
  <img src="https://github.com/user-attachments/assets/8e2a6488-dfbd-47ee-ac2a-d11fd732ae6d" width="700"/>
</p>

<p align="center"><i>Figure 1: Overview of trader performance under varying market sentiment conditions</i></p>

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Quant%20Finance-orange)


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

<p align="center">
  <img src="https://github.com/user-attachments/assets/6162963c-9a14-40b2-8516-528de2d4b020" width="700"/>
</p>

<p align="center"><i>Figure 2: Data processing and analytical pipeline</i></p>



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

### Sentiment Distribution

<p align="center">
  <img src="https://github.com/user-attachments/assets/a4348530-7daa-41aa-94d6-32e5f88c41e4" width="500"/>
</p>

<p align="center"><i>Figure 3: Distribution of trades across sentiment categories</i></p>


* Profitability by sentiment
* Win rate by sentiment
* Risk behavior across sentiment phases
* Trader-level performance aggregation
* Time-series PnL trend
* Correlation analysis

---

## 📊 Key Results

<p align="center">
  <img src="https://github.com/user-attachments/assets/ca7bd287-3030-41d5-be0d-839bf99aee89" width="750"/>
</p>

<p align="center"><i>Figure 4: Average PnL across sentiment regimes showing strong positive skew during Greed phases</i></p>



* Greed Avg PnL: **+$540**

* Fear Avg PnL: **-$310**

* **~2.7× performance difference**

* Higher win rates observed in bullish sentiment

* Risk exposure increases with positive sentiment

* Conservative positioning during fear phases

---

## 📉 Visual Insights

<p align="center">
  <img src="https://github.com/user-attachments/assets/36dbb1fa-2e15-417b-bc67-6df4401146db" width="500"/>
</p>

<p align="center"><i>Figure 5: Risk exposure trends across sentiment phases</i></p>



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
