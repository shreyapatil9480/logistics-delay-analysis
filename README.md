# Logistics Delay Analysis

Which customers are likely to churn?

**Stakeholder:** Customer Success Lead

## Key Insights

- Tenure under 6 months doubles churn risk for basic-tier accounts.
- Support ticket volume above 5 is a leading churn indicator.
- Premium tier churn is driven more by ticket severity than volume.

## Dataset

Primary file: `data/customer_tenure.csv`  
Target variable: `churned`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/analysis.ipynb
```


## Next Steps

**Done.** Weekly stakeholder report automation is implemented — see ### Implemented below.

---
*Analytics portfolio project — 2025-08*

<!-- build 5 -->

### Implemented

```bash
pip install -r requirements.txt
python scripts/weekly_report.py
```
### Report output

After running `python scripts/weekly_report.py`, open `reports/weekly_summary.html` for the stakeholder summary.

