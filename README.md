# Data_Science_internship_assigment
# Trader Behavior and Market Sentiment Analysis

This project analyzes the relationship between trader behavior and Bitcoin market sentiment using two key datasets:

- **Bitcoin Market Sentiment Dataset** — Contains daily market sentiment classification (`Fear` or `Greed`).
- **Historical Trader Data from Hyperliquid** — Contains detailed trade records including account info, trade size, execution price, profitability, and more.

---

## Objective

To understand how trading behavior (profitability, risk, volume, trade frequency) aligns with or diverges from overall market sentiment (Fear vs Greed). The goal is to identify hidden trends or signals that can help design smarter trading strategies adapted to market mood.

---

## Project Overview

- Data preprocessing and cleaning of both datasets.
- Feature engineering to compute daily aggregated trader metrics:
  - Total trades
  - Total volume traded
  - Win rate (ratio of profitable trades)
  - Average closed profit and loss (PnL)
  - Average trade size and execution price
- Merging trader behavior metrics with market sentiment data.
- Exploratory data analysis including correlation and visualization.
- Summary of actionable insights for trading strategy development.

---

## Getting Started

### Prerequisites

- Python 3.7+
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scipy
```
**Folder Structure**
ds_Aqsa_Chivelkar/
│
├── notebook_1.ipynb # Main Google Colab notebook
│
├── csv_files/ # Stores raw/processed CSVs
│ └── fear_greed_index_raw.csv
│ └── historical_data_raw.csv
│ └── trader_behavior_sentiment_analysis.csv 
│
│
├── outputs/ # Stores plots, charts, images
│ └── chart1.png
│
├── ds_report.pdf # Final summarized report
└── README.md # Project documentation
--------

