# ⚽ EPL 2023/24 Team Performance Dashboard

## 📌 Project Overview

This project focuses on analysing the **English Premier League (EPL) 2023/24 season** at a team level to understand how attacking output, defensive stability, and overall efficiency translate into league performance.

The analysis goes beyond league standings by evaluating performance efficiency, identifying overperforming and underperforming teams, and presenting insights through an interactive dashboard.

---

## 📊 Data Description
The project uses two processed datasets derived from raw match data:
### Team Match-Level Data
* One row per team per match
* Captures match outcomes from each team’s perspective
* Used for detailed performance analysis

### Team Summary Data
* Aggregated season-level statistics per team
* Used for KPIs, comparisons, and dashboard visuals

---

## 📂 Project Structure
* EPL-2023-24-Team-Performance/
  │
  ├── data/
  │   ├── raw/
  │   │   └── E0.csv
  │   │
  │   └── processed/
  │       ├── team_match_level.csv
  │       └── team_summary.csv
  │
  ├── notebook/
  │   └── analysis.ipynb
  │
  ├── visuals/
  │   ├──League dashboard.png
  │
  ├── dashboard/
  │   └── EPL_2023_24_Dashboard.pbix
  │
  |__ README.md

---

## 🔄 Analysis Workflow

* Raw match data loaded and cleaned using Python
* Match-level data reshaped into team-wise format
* Key performance metrics engineered (Goals, Points, PPM)
* Team-level season summaries created
* Clean datasets exported for dashboard use
* Interactive Power BI dashboard developed

---

## 📈 Key Insights

* Teams differ significantly in efficiency despite similar goal totals
* Defensive strength has a strong correlation with points accumulation
* Overperforming teams maximise points through balanced attack and   defence
* Raw goal counts alone do not fully explain league performance

---

## 🛠 Tools & Technologies
* Python (Pandas, NumPy)
* Power BI
* CSV datasets

## 🎯 Project Objective

 To demonstrate structured sports analytics thinking, data preparation, and dashboard-driven insight generation suitable for analytics and performance analysis roles.
