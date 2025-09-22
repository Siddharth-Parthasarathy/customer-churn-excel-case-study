# Databel Churn Project — Insights Summary

This project analyzes customer churn for **Databel**, using data preparation and dashboards built in Excel.  
The repo contains:
- **Raw dataset:** `1_1_data_preparation.xlsx`
- **Final analysis dashboards:** `3_5_final_solution.xlsx`

---

## 📊 Executive Summary
- **Churn rate:** 26.9% (1,796 of 6,687 customers).
- **Biggest churn drivers:**
  1. Month-to-month contracts (**46%** churn).
  2. Multiple support calls (≥3 calls → almost certain churn).
  3. Early-tenure customers (first 3–6 months).
  4. Higher monthly charges (> $40).
  5. International/data overage fees (*bill shock*).
- **At-risk groups:** seniors, paper check payers, unlimited plan users, solo customers.
- **Main churn reasons:** competitor offers, poor support experience, price/product dissatisfaction.
- **Retention levers:** push longer contracts, improve support quality, cap bill shock, bundle add-ons, expand family/group plans.

---

## 🔍 Methodology
1. **Data preparation**
   - Cleaned and structured raw customer records (6,687 rows).
   - Created tenure bands, price bands, and grouped support calls.
   - Verified churn labels and aggregated KPIs.

2. **Final dashboards (`3_5_final_solution.xlsx`)**
   - **Overview dashboard:** churn KPIs, revenue snapshot, tenure distribution.
   - **Churn analysis dashboard:** churn by contract, tenure, calls, pricing, demographics.
   - **Customer pivots:** state, payment method, plan type, add-ons, usage.

---

## 📈 Key Findings

### Contract & Tenure
- **Month-to-month:** 46.3% churn.  
- **One-year:** 11.3% churn.  
- **Two-year:** 2.8% churn.  
- Churn highest in first 3 months (**56.4%**), declines to **6.6%** after 5 years.

### Customer Support
- **0 calls:** 8.9% churn.  
- **3 calls:** 87.5% churn.  
- **4+ calls:** ~100% churn.  
➡️ Repeated support issues are the strongest churn predictor.

### Price & Plan
- ≤$20/month: **14.1%** churn.  
- $40–50/month: **38.1%** churn.  
- Unlimited plan: **32.1%** churn vs 16.1% for standard.  
- International usage active: **34.3%** churn vs 22.2%.  

### Demographics & Add-ons
- Seniors: **38.2%** churn vs under-30: **23.0%**.  
- Solo customers: **33%** churn vs group/family: **6–8%**.  
- Bundles (backup + device protection): **23%** churn vs **29%**.  

### Payment Method
- Credit card: **14.5%** churn.  
- Direct debit: **34.5%**.  
- Paper check: **38.0%**.  

### Churn Reasons
- **Competitor offers:** 805 (better devices, offers, speeds, data).  
- **Service attitude issues:** 287.  
- **Price/product dissatisfaction:** 200–286.  
➡️ Competition is the #1 stated reason; support attitude is #2.

---

## 📊 Dashboard Insights

### 📊 Churn Overview Dashboard
![Churn Dashboard](02b4fa95-4a9f-4c79-8512-3e0029ac1d1b.png)

*➡️ Competitor offers and poor service experience drive churn, with highest risk among heavy data users and certain states.*

---

### 👥 Demographics & Usage Dashboard
![Demographics & Usage](418d42df-bfc9-40bf-9ac8-5dd0f913720e.png)

*➡️ Seniors and mid-range data users churn the most, making them prime targets for retention programs.*

---

### ❌ Churn Reasons Breakdown
![Churn Reasons](61d90538-7270-4ede-9064-0696c5a17362.png)

*➡️ Competitor offers and poor service attitudes explain most of the churn reasons reported.*

---

### 🏆 Competitor Churn Analysis
![Competitor Churn](3f7d9374-8c64-4ef4-9874-96a1ad28e238.png)

*➡️ Nearly three-quarters of competitive churn is due to rivals’ better offers and devices.*

---

## ✅ Recommendations
1. **Pre-empt M2M churn** → offer discounts/loyalty rewards at 30/60/90 days.  
2. **Triage high-call customers** → auto-route to retention specialists.  
3. **Plan redesign** → smooth price bands, cap international/data overages to reduce *bill shock*.  
4. **Encourage contract upgrades** → incentives like device credits.  
5. **Promote bundles & family/group plans** → strongest retention effect.  
6. **Train support staff** → attitude issues are a top churn trigger.  

---

## 📂 Repo Structure
- `1_1_data_preparation.xlsx` → cleaned dataset.  
- `3_5_final_solution.xlsx` → dashboards & pivots.  
- `README.md` → insights & project documentation.  

---

## 📷 Dashboard Gallery
A quick visual tour of the dashboards with key one-line insights:

- ![Churn Dashboard](02b4fa95-4a9f-4c79-8512-3e0029ac1d1b.png)  
  *Competitor offers and poor service experience drive churn, with highest risk among heavy data users and certain states.*

- ![Demographics & Usage](418d42df-bfc9-40bf-9ac8-5dd0f913720e.png)  
  *Seniors and mid-range data users churn the most, making them prime targets for retention programs.*

- ![Churn Reasons](61d90538-7270-4ede-9064-0696c5a17362.png)  
  *Competitor offers and poor service attitudes explain most of the churn reasons reported.*

- ![Competitor Churn](3f7d9374-8c64-4ef4-9874-96a1ad28e238.png)  
  *Nearly three-quarters of competitive churn is due to rivals’ better offers and devices.*

---

## 🚀 Takeaway
Churn is driven less by *who* the customers are and more by **contract type, support experience, and bill shock**.  
By focusing on **longer contracts, proactive support, and reducing overages**, Databel can cut churn dramatically while boosting customer lifetime value.
Churn is driven less by *who* the customers are and more by **contract type, support experience, and bill shock**.  
By focusing on **longer contracts, proactive support, and reducing overages**, Databel can cut churn dramatically while boosting customer lifetime value.
