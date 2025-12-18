# Call Center QA Auto-Fail Analysis

## Project Overview
This project analyzes QA auto-fail data from a call center environment with limited call sampling. Using Excel Online, I built a dashboard to identify dominant compliance failure drivers, highlight team-level risk concentration, and support data-driven calibration discussions.

---

## Business Problem
QA teams were only able to grade one call per representative per month, limiting visibility into systemic compliance issues. Leadership needed a way to identify high-risk behaviors and teams despite incomplete sampling.

---

## Tools Used
- Excel Online
- PivotTables
- Slicers
- Lookup formulas (VLOOKUP)
- Data cleaning & helper columns

---

## Analysis Approach
- Normalized raw QA auto-fail data with helper columns (Status, Month, Team Lead)
- Segmented active vs attrited representatives to preserve historical accuracy
- Built PivotTables to calculate auto-fail distribution by failure reason and team
- Designed a dashboard with KPIs, trend visuals, and written insights

---

## Key Insights
- Recording Disclaimer failures accounted for **74%** of all auto-fails among active representatives
- Two teams contributed **75%** of total auto-fails, indicating risk concentration
- Targeted compliance coaching would likely be more effective than organization-wide retraining

---

## Repository Contents
- `/data/` — Raw and cleaned datasets
- `/screenshots/` — Dashboard and pivot table visuals
- `README.md` — Project documentation

---

## Next Steps
- Rebuild this analysis in PostgreSQL
- Create Tableau visualizations from the same dataset
- Expand analysis to include trend and cohort comparisons

