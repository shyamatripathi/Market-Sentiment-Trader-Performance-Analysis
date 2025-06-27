# Market Sentiment & Trader Performance Analysis

This project analyzes the relationship between **market sentiment** (Fear/Greed Index) and **trader performance** using historical trading data. It aims to uncover patterns that can help develop smarter and safer trading strategies.

---

## Objective

Explore how market sentiment affects trader behavior and profitability by:

- Merging sentiment and trading datasets
- Visualizing trading activity across sentiment phases
- Evaluating PnL distribution, trade volume, and risk-adjusted returns

---

## Tech Stack

- **Python 3.8+**
- **Pandas** – data preprocessing
- **Matplotlib** & **Seaborn** – visualizations
- **Jupyter Notebook** / Python script

---

## Dataset Overview

| File | Description |
|------|-------------|
| `historical_data.csv` | Trade-level data including timestamps, PnL, size, leverage |
| `fear_greed_index.csv` | Daily sentiment classification (Fear, Greed, etc.) |

---

## Key Visualizations

- **Bar Plot**: Average Closed PnL per sentiment phase
- **Count Plot**: Number of trades by sentiment
- **Violin Plot**: PnL distribution (for risk insight)
- **Line Plot**: Daily average PnL trends
- **Top Coins**: Best-performing symbols during fear/greed

---

## Sample Insights

- 📈 Traders on average perform **better during Fear and Greed** sentiment.
- 📉 Trade volume drops significantly during **Neutral** periods.
- 🧠 Some coins show consistent performance based on sentiment phase.
- 📊 “Fear” shows **more stable** PnL compared to “Greed” in risk-adjusted terms.

---

## How to Run

1. **Install requirements**:

```bash
pip install pandas matplotlib seaborn
