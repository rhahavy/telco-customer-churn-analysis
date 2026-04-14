# 📊 Telco Customer Churn Analysis — Interactive Dashboard

A portfolio-grade interactive dashboard analyzing customer churn patterns for a fictional telecom company. Built to surface actionable business insights and identify high-risk customer segments.

**[🔗 View Live Dashboard](https://YOUR_USERNAME.github.io/telco-customer-churn-dashboard/)**

![Dashboard Preview](preview.png)

---

## Business Problem

Customer churn directly impacts recurring revenue. This analysis answers:

- Which customer segments are most likely to leave?
- What service and contract factors drive churn?
- Where should the company focus retention efforts for maximum ROI?

## Key Findings

| Insight | Detail |
|---|---|
| **Contract type is the #1 predictor** | Month-to-month customers churn at 42.7% vs 2.8% for two-year contracts |
| **The first 6 months are critical** | 52.9% of customers who joined within the last 6 months have already left |
| **Electronic check = red flag** | 45.3% churn rate — nearly 3× higher than autopay methods |
| **Support services cut churn in half** | Adding tech support or online security drops churn from ~42% to ~15% |
| **$1.67M in annual revenue at risk** | Churned customers represent $139K in lost monthly recurring revenue |

## Recommended Actions

1. **Incentivize annual contracts** — offer 15% discount for switching from month-to-month
2. **Bundle tech support & security** — include free for first 3 months to drive adoption
3. **Fix electronic check friction** — migrate users to autopay with a $5/month credit
4. **Onboarding program** — implement touchpoints at 30, 60, and 90 days for new customers

## Dashboard Features

- **4 KPI cards** — total customers, churn rate, avg revenue, high-risk percentage
- **Revenue-at-risk banner** — frames the financial stakes immediately
- **6 interactive charts** — contract type, payment method, tenure, services, charges, demographics
- **Risk segmentation** — ranks the most dangerous customer profiles
- **3 dynamic filters** — contract type, internet service, senior citizen status
- **Insight panel** — 6 data-backed findings with concrete recommendations
- **Fully responsive** — works on desktop and mobile

## Tech Stack

- **HTML / CSS / JavaScript** — single-file, zero dependencies
- **Data** — IBM Telco Customer Churn dataset (7,043 customers, 21 features)
- **Deployment** — GitHub Pages ready

## Dataset

Source: [IBM Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) via Kaggle

7,043 customer records with demographics, account information, service subscriptions, and churn labels.

## How to Run Locally

```bash
git clone https://github.com/YOUR_USERNAME/telco-customer-churn-dashboard.git
cd telco-customer-churn-dashboard
open index.html
```

No build step, no dependencies, no server required. Just open the HTML file.

---

Built as a portfolio project by Rhahavy Bala
