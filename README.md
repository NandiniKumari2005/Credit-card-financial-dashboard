# 💳 Credit Card Portfolio Analytics

> End-to-end analytics project turning raw credit card data into actionable business insights — built with SQL, DAX, and Power BI.

---

## Overview

This project analyzes a bank's credit card portfolio from two angles:

- **Customers** — who they are, what they earn, and where revenue comes from
- **Transactions** — how they actually spend, on which cards, and through which channels

Raw data is cleaned and modeled with SQL, enriched with DAX measures, and visualized across two Power BI dashboards. A written report ties both together with key findings and recommendations.

---

## What's Inside

```
├── Credit Card Financial Dashboard-Customer.pdf   → Customer dashboard (Power BI export)
├── Credit_Card_Transaction_Dashboard.pdf          → Transaction dashboard (Power BI export)
├── Credit_Card_Portfolio_Analytics_Report.pdf     → Combined summary report
├── credit_card.xlsx                               → Source data (accounts/cards)
├── customer.xlsx                                  → Source data (customer demographics)
├── credit_card_report.docx                        → Supporting write-up
├── SQL Query - Financial Dashboard Data.sql        → Data prep / modeling queries
└── DAX QUERIES.txt                                → DAX measures used in the dashboards
```

---

## Dashboard 1 — Customer Financial Dashboard

Answers: *who are our customers, and where does revenue come from?*

| Metric | Value |
|---|---|
| Total Revenue | 55.4M |
| Total Interest | 7.9M |
| Total Income | 577M |
| CSS | 3.19 |

Sliced by age, gender, salary band, marital status, education, dependents, state, and job type.

## Dashboard 2 — Transaction Dashboard

Answers: *how are customers spending, and on which cards?*

| Metric | Value |
|---|---|
| Revenue | 10.23M |
| Transaction Amount | 8M |
| Total Interest | 1.35M |
| Transaction Count | 168K |

Sliced by card category, use-chip channel, expenditure type, education, and quarter.

---

## Key Findings

- 🏆 **Self-employed customers & graduates** top revenue charts in both dashboards
- 💳 **Blue tier drives ~95%** of transaction revenue — a concentration risk
- 📉 **Swipe dominates** (8M) over Chip/Online (1M each) — low digital adoption
- 📊 **Q3 dip** in transaction count despite steady revenue — worth investigating

Full breakdown in `Credit_Card_Portfolio_Analytics_Report.pdf`.

---

## Tech Stack

`SQL` · `DAX` · `Power BI` · `Excel`

---

## How to Use

1. Clone this repo
2. Open the `.pbix` file in Power BI Desktop (if included) to explore live
3. Check `SQL Query - Financial Dashboard Data.sql` for the data model
4. Check `DAX QUERIES.txt` for measure logic
5. Read the PDF report for the narrative summary

---

## Notes

- Currency in lakhs/crores (Indian numbering convention), matching the source dashboards
- Sample/illustrative data for portfolio demonstration purposes
