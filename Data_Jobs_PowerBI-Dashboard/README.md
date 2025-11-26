# 📊 Data Jobs Salary & Market Insights Dashboard (Power BI)

This Power BI dashboard provides a complete visual analysis of the global **data job market**, including salary trends, job role comparisons, hiring platforms, remote work insights, and country-wise job distribution.

It helps anyone exploring careers in **data analytics, data engineering, data science, and cloud roles** understand:

- 🏆 Highest-paying data jobs
- 💰 Yearly vs. hourly salary comparison
- 🌍 Geographic job availability
- 🎓 Degree requirement statistics
- 🏢 Job types (Full-time, contract, internship)
- 🧭 Trends in data job postings throughout the year

---

## 🚀 Project Overview

This dashboard includes multiple analysis pages:

| Page Name | Insights Covered |
|----------|------------------|
| Home | Navigation UI to explore all chart types |
| Column & Bar Charts | Salary rankings and role-wise comparisons |
| Line & Area Charts | Job posting trends and salaries over time |
| Common Charts | Pie, donut & scatterplot analysis (WFH %, No-degree %, salary vs hourly) |
| Map Charts | Worldwide job availability & highest-paying countries |
| Uncommon Charts | Treemap, drilldown visuals & stacked comparisons |
| Tables | Detailed job records with job type badges and bar-indicators |
| Cards | KPI-style metrics and comparison table formatting |
| Slicers | Filtering based on job title, salary range, posting date |
| 📌 Data Jobs Dashboard | Main executive dashboard with KPIs, trends & job insights |
| 🔍 Job Title Drill Through | Detailed insight for each selected job title |

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modeling & dashboard creation |
| **Power Query** | ETL, cleaning & transformation |
| **DAX** | Calculations (Median Salary, KPI formats) |


---

## 📈 Key KPIs Included

✔ Median Yearly Salary  
✔ Median Hourly Salary  
✔ Job Count  
✔ Salary Trend Line  
✔ Star Rating Indicator  
✔ Platform-wise job availability  

---

## 🔍 Main Calculated Measures (DAX)

```DAX
Median Yearly Salary = MEDIAN('Dataset'[salary_year_avg])

Median Hourly Salary = MEDIAN('Dataset'[salary_hour_avg])

Salary (Formatted) = FORMAT([Median Yearly Salary], "$#,,K")
```
