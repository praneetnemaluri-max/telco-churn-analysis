# telco-churn-analysis
End-to-end customer churn analysis using Python, Scikit-learn and XGBoost. Identifies €175K in recoverable revenue from a 7,032-customer telecoms dataset.
# Customer Churn Analysis
### Telco Customer Retention — End-to-End Analytics Project

**Author:** Praneet Nemaluri | MSc Business Analytics, University of Galway | May 2026

---

## The Business Problem

A telecommunications company is losing more than one in four customers every month. 
This project was built to answer three questions a Head of Retention would actually ask:

- Where is churn concentrated — which customers are most at risk?
- Can we predict who will leave before they do?
- What is the financial return of acting on those predictions?

---

## Key Findings

| Metric | Value |
|--------|-------|
| Monthly churn rate | 26.6% |
| Annual revenue at risk | €1.67M |
| Month-to-month churn rate | 42.7% |
| Electronic check churn rate | 45.3% |
| Best model AUC-ROC | 0.836 |
| Projected campaign ROI | 4,066% |

---

## What I Built

- **Exploratory Data Analysis** — identified contract type, tenure, and payment method 
as the three primary churn drivers
- **Feature Engineering** — created `num_services`, `is_autopay`, and `avg_monthly_spend` 
to better capture customer behaviour
- **Three ML Models** — Logistic Regression, Random Forest, XGBoost
- **Business Case** — translated model output into €175,648 net benefit from a €4,320 
retention campaign

---

## Files

| File | Description |
|------|-------------|
| `churn_analysis.ipynb` | Full annotated notebook |
| `Churn_Analysis_Report.pdf` | Professional report with findings and recommendations |

---

## Tools & Libraries

Python · Pandas · Scikit-learn · XGBoost · Matplotlib · Seaborn · ReportLab

---

## How to Run

1. Download the notebook and dataset
2. Open in Google Colab or Jupyter
3. Run all cells in order
