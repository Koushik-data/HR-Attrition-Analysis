# HR Attrition Analytics Dashboard

## 📌 Project Overview
This project presents a professional HR Attrition Analytics Dashboard built using Power BI to analyze employee attrition trends, workforce demographics, job satisfaction, and retention drivers. The dashboard helps HR teams and business stakeholders make data-driven decisions to improve employee retention and workforce management.

---

## 🎯 Business Problem
Employee attrition leads to increased hiring costs, productivity loss, and workforce instability. The objective of this project is to identify the key factors affecting employee turnover and provide actionable HR insights through interactive visualizations.

---

## 🛠️ Tools & Technologies
- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## 📊 Dashboard Features

### KPI Metrics
- Total Employees
- Attrition Count
- Attrition Rate
- Active Employees
- Average Age
- Average Years at Company

### Interactive Visualizations
- Department-wise Attrition Analysis
- Employees by Age Group
- Job Satisfaction Analysis
- Education Field Attrition
- Gender-wise Attrition Analysis
- Dynamic Filters & Slicers

---

## 📈 Key Insights
- R&D department has the highest employee attrition.
- Employees aged 25–34 are most likely to leave the organization.
- Overtime significantly impacts employee attrition.
- Lower job satisfaction ratings correlate with higher attrition.
- Life Sciences and Medical education fields contribute the most to employee turnover.

---

## 🧮 DAX Measures Used

```DAX
Total Employees =
COUNT('HR Data'[Employee Number])

Attrition Count =
CALCULATE(
    COUNT('HR Data'[Employee Number]),
    'HR Data'[Attrition] = "Yes"
)

Active Employees =
[Total Employees] - [Attrition Count]

Attrition Rate =
DIVIDE(
    [Attrition Count],
    [Total Employees],
    0
)

Average Age =
AVERAGE('HR Data'[Age])

Average Years at Company =
AVERAGE('HR Data'[Years At Company])
```

---

## 🖥️ Dashboard Preview

 <img width="1457" height="805" alt="HR-Attrition-PowerBI-Dashboard" src="https://github.com/user-attachments/assets/4e768a0a-3907-469a-aa39-ce5666fff8fe" />


---

## 🎯 Business Impact
This dashboard helps organizations:
- Monitor employee attrition trends
- Identify high-risk employee groups
- Improve retention strategies
- Enhance workforce planning
- Support HR decision-making with data

---

## 👨‍💻 Author
Koushik Das

Data Analyst | Power BI | SQL | Excel | Python
# 📞 Contact

- 📧 Email: datawithkoushik@gmail.com
- 📱 Phone: +91 6290610739
- 💼 LinkedIn: https://www.linkedin.com/in/koushik-das-71a2a8220/
- 🌐 GitHub: https://github.com/Koushik-data
---

## ⭐ Project Outcome
Successfully developed an interactive HR Analytics Dashboard providing executive-level insights into workforce behavior, employee attrition patterns, and HR performance indicators.
