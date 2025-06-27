# Historical-Stock-Analysis
This project analyzes the historical **stock prices** and **revenue data** for two major companies: **Tesla (TSLA)** and **GameStop (GME)**. Using data visualization and Python programming, we aim to understand how revenue correlates with stock price movements over time.

---

## 📌 Objectives

- Retrieve historical stock data using `yfinance`
- Import and clean historical revenue data
- Visualize trends in share prices and revenues
- Combine insights to interpret performance patterns

---

## 📁 Files

| File | Description |
|------|-------------|
| `Tesla.ipynb` | Jupyter notebook analyzing Tesla’s stock and revenue |
| `GME.ipynb` | Jupyter notebook analyzing GameStop’s stock and revenue |
| `tesla.csv` | Tesla revenue data (manually sourced or scraped) |
| `gme.csv` | GameStop revenue data (manually sourced or scraped) |
| `README.md` | Project documentation |

---

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- `yfinance` for stock data
- `pandas` for data manipulation
- `plotly` for interactive visualization

---

## 📊 Sample Visualizations

Each notebook generates two vertically stacked line charts:

1. **Stock Closing Prices**
2. **Quarterly Revenue**

These plots help in identifying correlations between market behavior and financial performance.

---

## 🧹 Data Cleaning Notes

- Revenue figures cleaned using regex to remove `$` and `,` characters.
- Dates formatted using `pandas.to_datetime()` for consistency.

---
🧠 Insights
Tesla shows a strong positive trend in both stock and revenue, especially post-2019.

GameStop has volatile stock prices with relatively stable but declining revenue until its 2021 surge.

👤 Author
Teesta Sarkar
B.Tech CSE (AI/ML) | Data Science & ML Enthusiast

