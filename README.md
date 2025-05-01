# Quantitative Research Simulation – Natural Gas Pricing & Credit Risk Modeling

This project is based on the **J.P. Morgan Quantitative Research Virtual Experience Program** hosted on [Forage](https://www.theforage.com/), where participants simulate real-world QR workflows that support both trading and risk management decisions.

---

## Project Overview

This repository contains two core modules:

### 1. Natural Gas Storage Contract Valuation
- Forecast natural gas prices using Holt-Winters exponential smoothing
- Interpolate and extrapolate prices on any date
- Compute the net present value of a gas storage contract based on injection/withdrawal dates, fees, and storage costs

### 2. Credit Risk & Expected Loss Modeling
- Train classification models (Logistic Regression, XGBoost) to predict probability of loan default
- Calculate expected loss (EL) using the formula:  
  $$ EL = PD \times EAD \times (1 - \text{Recovery Rate}) $$
- Discretize FICO scores into quantile-based buckets and visualize the relationship with default rate

---

## Tech Stack

- Python (pandas, scikit-learn, statsmodels, matplotlib, xgboost)
- Time Series Modeling (Holt-Winters)
- Credit Scoring & Risk Analytics
- Jupyter Notebook

---

## Folder Structure
```
project-root/
├── notebooks/
│   └── JP_Morgan_QR_Complete.ipynb     # Main project notebook
├── data/
│   ├── Nat_Gas.csv                     # Natural gas pricing data
│   └── Loan_Data.csv                   # Loan book for credit risk modeling
└── README.md
```
---

## Outcome

This project demonstrates how quantitative researchers apply data science to:
- Support energy traders with predictive price models
- Assist risk managers in quantifying credit exposure and loss
- Develop interpretable tools for decision-making across trading desks and banking products

---

## Author

Xi Li
