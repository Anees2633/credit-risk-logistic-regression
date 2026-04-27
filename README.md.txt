# credit-risk-logistic-regression

Predicting credit card default risk using Logistic Regression, comparing **Scikit-learn** and **Statsmodels** on a dataset of 45,528 customers.

---

## Dataset
- **File:** `Credit_risk_assesment.csv`
- **Records:** 45,528
- **Target:** `credit_card_default` (0 = No Default, 1 = Default)

---

## Libraries Used
- `pandas`, `numpy` — data processing
- `matplotlib`, `seaborn` — visualizations
- `scikit-learn` — Model 1
- `statsmodels` — Model 2

---

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

---

## Results

| Metric | Scikit-learn | Statsmodels |
|---|---|---|
| Accuracy | 98.00% | 98.01% |
| Recall (Default) | 0.80 | 0.80 |
| F1-Score (Default) | 0.87 | 0.87 |
| AUC Score | 0.993 | 0.994 |

---

## Usage

```bash
jupyter notebook credit_risk.ipynb
```

---

## Module
CO7024 — Statistical Programming | University of Chester