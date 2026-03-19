# Tableau-Sales-Customer-Dashboard
## 📌 Overview

A two-dashboard Tableau system built for a retail business to replace manual reporting with always-live, self-serve intelligence. Four data tables were unified into a single model powering dynamic year-over-year comparisons across **2020–2023**.

> A single **Select Year parameter** controls every metric across both dashboards instantly — no data team, no manual refresh required.

---

## 🛠️ Tools & Techniques

| Tool | Purpose |
|---|---|
| **Tableau** | Dashboard design & data modelling |
| **DAX Calculated Fields** | Current year vs. previous year metric logic |
| **LOD Expressions** | Distinct customer counts independent of view context |
| **Window Functions** | Auto-labelling best & worst performing weeks |
| **Parameters** | Single year-selector controlling all metrics |
| **KPI Design** | Directional flags for instant performance signals |

---

## 📊 Dashboard Breakdown

### 🛒 Sales Dashboard
Tracks **Sales, Profit, and Orders** with weekly granularity. Automated `WINDOW_MAX` / `WINDOW_MIN` highlights surface the best and worst performing weeks instantly. A subcategory comparison makes growth vs. decline impossible to miss.
```
Declining profit + Rising sales     →  Margin conversation
Declining profit + Declining sales  →  Strategic conversation
```

### 👥 Customer Dashboard
Tracks **Total Customers, Sales Per Customer, and Orders Per Customer** year-over-year — distinguishing whether growth is driven by frequency *(defensible)* or pure acquisition *(fragile)*. A **Top Customers** view surfaces the highest revenue concentration risks.

---

## 📈 Key Results

| Metric | YOY Change | Signal |
|---|---|---|
| Total Sales | **+20.4%** | ✅ Growing |
| Total Profit | **+14.2%** | ✅ Growing |
| Orders Per Customer | **+28.0%** | ✅ Frequency rising |

---

## 💡 Recommendations

- 🎯 **Depth over volume** — if Sales Per Customer falls while customer count rises, shift focus to retention.
- 📅 **Replicate peak weeks** — use Min/Max insights to engineer high-performing conditions intentionally.
- 📉 **Subcategory threshold** — trigger a formal review for any subcategory declining **>10% YOY**.
- 🤝 **Monitor top customers** — a declining order frequency from high-value customers is an early warning sign.

---
