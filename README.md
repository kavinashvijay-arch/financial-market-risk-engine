# 📈 Financial Market Risk Engine

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Monte Carlo](https://img.shields.io/badge/Simulation-Monte%20Carlo-purple)
![Finance](https://img.shields.io/badge/Financial-Risk-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🚀 Run the Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Sf1NOHnTNAKR_6_4EdMEha_WqIHQOznY?usp=drive_link)

---

# 📌 Project Overview

Financial institutions must estimate potential portfolio losses before making investment decisions. This project develops a market risk engine capable of estimating downside risk using Historical Value-at-Risk (VaR), Monte Carlo simulation, and Expected Shortfall (ES).

---

# 🎯 Business Problem

Portfolio managers require quantitative measures of downside risk to determine capital requirements and investment exposure.

This project estimates:

- Historical Value-at-Risk
- Monte Carlo Value-at-Risk
- Expected Shortfall
- Monetary portfolio losses

---

# 📂 Dataset

Historical market prices downloaded using **Yahoo Finance**.

Assets analysed:

- User-selected equity portfolio

---

# ⚙ Project Workflow

```
Historical Prices
      │
      ▼
Daily Returns
      │
      ▼
Portfolio Returns
      │
      ▼
Historical VaR
      │
      ▼
Monte Carlo Simulation
      │
      ▼
Expected Shortfall
      │
      ▼
Risk Report
```

---

# 📈 Risk Models

Implemented:

- Historical VaR
- Historical Expected Shortfall
- Monte Carlo VaR
- Monte Carlo Expected Shortfall

---

# 📊 Outputs

The engine calculates:

- Mean Portfolio Return
- Portfolio Volatility
- Historical VaR
- Historical ES
- Monte Carlo VaR
- Monte Carlo ES
- Monetary Loss Estimates

---

# 💼 Business Value

The project demonstrates practical market risk measurement techniques used by banks, asset managers, insurance companies, and investment firms to estimate downside risk and support capital allocation decisions.

---

# 📊 Key Features

✔ Historical Simulation

✔ Monte Carlo Simulation

✔ Expected Shortfall

✔ Monetary Loss Conversion

✔ Portfolio Risk Analytics

---

# 📁 Repository Structure

```
Market-Risk-Engine/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

# 🛠 Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- yfinance

---

# 🚀 Future Improvements

- GARCH Volatility Models
- Portfolio Optimisation
- Risk Dashboard
- Backtesting
- Kupiec Test
- Multi-Asset Portfolio Analysis

---

# 👨‍💻 Author

**Kavinash Vijay**

