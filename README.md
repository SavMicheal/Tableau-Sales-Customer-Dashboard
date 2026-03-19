# Tableau-Sales-Customer-Dashboard
 Overview
A two-dashboard Tableau system built for a retail business to replace manual reporting with always-live, self-serve intelligence. Four data tables — Orders, Customers, Products, and Location — were unified into a single model powering dynamic year-over-year analysis across 2020–2023.
A single Select Year parameter controls every metric across both dashboards instantly — no data team, no manual refresh.

🛠️ Tools & Techniques
Tableau  |  DAX Calculated Fields  |  LOD Expressions  |  Window Functions  |  Parameters  |  KPI Design

📊 Dashboard Breakdown
Sales Dashboard
Tracks Sales, Profit, and Orders with weekly granularity. Automated Min/Max highlights surface the best and worst performing weeks instantly. A subcategory comparison view makes growth vs. decline visible at a glance — declining profit on rising sales flags a margin issue; declining on both flags a strategic one.
Customer Dashboard
Tracks Total Customers, Sales Per Customer, and Orders Per Customer year-over-year. Distinguishes whether growth is driven by frequency (defensible) or pure acquisition (fragile). A Top Customers view surfaces the individual relationships with the highest revenue concentration risk.

📈 Key Results
MetricYOY ChangeTotal Sales+20.4%Total Profit+14.2%Orders Per Customer+28.0%

💡 Key Recommendations

Depth over volume — if Sales Per Customer is falling while customer count rises, shift focus to retention.
Replicate peak weeks — use Min/Max insights to engineer high-performing conditions intentionally.
Subcategory threshold — trigger a formal review for any subcategory declining more than 10% YOY.
Monitor top customers — declining order frequency from high-value customers is an early warning sign.
