# 📱 The Mobile Plus — Mobile Retail Sales Intelligence Dashboard

> **Turning 3,835 raw point-of-sale transactions into a boardroom-ready Power BI story — across 19 cities, 4 years, and ₹76.9 Cr in revenue.**

---

## 📸 Dashboard Preview

![The Mobile Plus — Executive Summary Cover](cover.jpg)

---

## 🧭 What Is This?

A fully interactive **Power BI Analytics Project** built on transaction-level point-of-sale data from **Mobile Plus**, a multi-city mobile phone retailer. The dashboard was built to answer one guiding question:

> *Where is Mobile Plus winning, where is revenue leaking, and what should happen next?*

It does this across three connected screens:

- 💰 **Sales Overview** — what's selling, where, and through which channel
- 📈 **Month-to-Date Growth** — is this month pacing ahead of or behind plan
- 🔁 **Year-over-Year Comparison** — is growth accelerating, flattening, or reversing

---

## ⚡ Key Metrics at a Glance

| Metric | Value |
|---|---|
| 💵 Total Revenue | ₹76.9 Cr |
| 🧾 Transactions | 3,835 |
| 📦 Units Sold | 19,150 |
| 🌍 Cities Covered | 19 |
| 📅 Time Period | Oct 2021 – 2024 |
| 📱 Brands Tracked | 5 (Apple, Samsung, OnePlus, Vivo, Xiaomi — 15 models) |
| 💳 Payment Channels | UPI, Debit, Credit, Cash |

> *All KPIs are slicer-driven and recalculate live by Year, Quarter, Month, and Day.*

---

## 🛠️ Tech Stack

```
Microsoft Power BI
├── Power Query      → Data ingestion & cleaning (14-field POS export)
├── Data Modelling    → Transaction-level schema across brand, city, payment, ratings
├── DAX              → Measures for Sales, AOV, MTD Growth, SPLY comparisons
├── Slicers          → Year / Quarter / Month / Day for real-time filtering
└── Report Pages      → Sales Overview · MTD Growth · YoY Comparison
```

---

## 📊 Screens Inside the Dashboard

| Screen | Purpose |
|---|---|
| 📶 Sales Overview | Total Sales, Quantity, Transactions & AOV — drill down by brand, model, payment method |
| 📈 MTD Growth | Cumulative Month-to-Date curve benchmarked against Same-Period-Last-Year |
| 🔁 YoY Comparison | Quarter- and month-level growth trends across 2021–2024 |

---

## 💡 Top Business Insights

1. **No single model dominates** — iPhone SE, OnePlus Nord & Galaxy Note 20 are tightly bunched at ₹56M–₹60M each.
2. **Payment mix carries zero channel risk** — UPI, Debit, Credit and Cash each sit at a balanced 24–26%.
3. **Delhi & Mumbai concentration** — revenue leans heavily on two metros, with a long tail of mid-size cities trailing behind.
4. **Ratings lean positive but not clean** — 61% "Good" vs. a sizeable 22% "Poor" tail worth root-causing.
5. **Growth has plateaued post-2022** — Qtr-1 2024 posted the first quarter-level YoY dip in the dataset.
6. **Demand is weekday-led, not weekend-driven** — sales peak Monday and taper steadily toward Thursday.

---

## 🎯 Key Recommendations

| # | Recommendation |
|---|---|
| 01 | Diagnose the "Poor" rating segment (~22% of orders) — fastest lever on margin & loyalty |
| 02 | Expand beyond Delhi–Mumbai into similar-profile mid-tier cities |
| 03 | Institutionalize MTD pace-tracking with a mid-month checkpoint + forecasted run-rate line |
| 04 | Investigate the Qtr-1 2024 YoY dip and the post-2022 growth plateau at brand/model level |
| 05 | Build weekday- and February-specific promotional calendars |
| 06 | Layer forecasting and target lines into MTD & YoY views — move from descriptive to predictive |


---

## 👤 About

Built by **Yatharth Aphale** as part of a hands-on **Business & Data Analytics Portfolio**.

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/Yatharth-2206)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/yatharth-aphale-338b203b8)

*⭐ If you found this useful, drop a star — it helps others discover the project!*
