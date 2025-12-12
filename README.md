# Workforce Equality Analysis

_A data-driven evaluation of fairness across factories and job roles using the Equality Score metric._  

---
## Overview
This project evaluates workforce fairness using an **Equality Score** (range: -100 to +100) and classifies roles into:
- **Fair** (±10)  
- **Unfair** (±11 to ±20)  
- **Highly Discriminative** (beyond ±20)  
Classification and visuals were produced in Excel. 

---

## Features
- Data processing & classification via Excel formulas  
- Equality Class column generation (role-level)  
- Visuals: Pie chart (class distribution) & Bar chart (average score by factory)  
- Insights and HR-focused recommendations  
- Final report exported as PDF (`workforce_report.pdf`) and workbook (`workForceanalysis.xlsx`) 
---

## Key Findings
- Majority of roles are **Fair** (≈51%). 
- Notable portions are **Unfair** (~30%) and **Highly Discriminative** (~19%). (See Pie Chart, page 3.) 
- Factories such as **Shenzhen** and **Meiyo** show negative average scores — recommend targeted audits. (Bar Chart, page 3.)  
- Inequality is often **role-specific**, not always factory-wide. 
---

## Recommendations
1. Prioritize HR review for **Highly Discriminative** roles. 
2. Run **factory-level equality audits** for factories with negative averages. 
3. Train managers on unbiased evaluation & compensation.  
4. Standardize HR policies and pay bands across factories.  
5. Re-evaluate job responsibilities for repeatedly unfair roles.

---

## Repository Contents
- `workforce_report.pdf` — Final report (visuals + insights). 
- `workForceanalysis.xlsx` — Dataset, formulas, and charts used for analysis.

---

## How to Reproduce
1. Open `workForceanalysis.xlsx`.  
2. Confirm the **Equality Score** column and the Excel formula that maps scores to **Equality Class** (Fair / Unfair / Highly Discriminative).  
3. Recreate charts: Pie chart for class distribution; Bar chart for average equality score by factory.  
4. Export the final report to PDF.

---

## Conclusion
Overall workforce equality is acceptable in many roles, but targeted interventions are required for specific roles and factories to correct persistent inequality patterns. Visual dashboards in the workbook provide actionable guidance for HR. 
