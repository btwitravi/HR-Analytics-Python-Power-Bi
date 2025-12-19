# 📊 HR Attrition Analytics | Python & Power Bi

## 📌 Project Overview
Employee attrition is a major challenge for organizations, leading to increased hiring costs, productivity loss, and workforce instability.
This project analyzes employee attrition patterns using HR data to identify key drivers behind employee turnover and support data-driven retention strategies.
The analysis combines exploratory data analysis (EDA) with an interactive Power BI dashboard to provide both high-level monitoring and root-cause insights.

## 🎯 Problem Statement
Organizations struggle to retain skilled employees when the underlying causes of attrition are not identified early.
The objective of this project is to analyze HR data to understand why employees leave or stay, focusing on factors such as job role, compensation, experience, overtime, job satisfaction,
promotions, and commute distance.

## 🧰 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning & EDA
- **Power BI** – Interactive dashboards & KPIs
- **Excel / CSV** – Raw data source

 ## 📂 Dataset
- **Records:** 1,470 employees
- **Type:** HR Employee Attrition Dataset
- **Target Variable:** Attrition (Yes / No)

 ## 🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand employee demographics, job characteristics, compensation, experience, and work conditions.

## Key focus areas:
- Age, income, experience, and tenure patterns
- Department and job role distribution
- Overtime, promotions, and job satisfaction impact
- Correlation between age, income, and experience

📄 Detailed EDA is available in:

- HR_Attrition_EDA.ipynb
- HR_Attrition_EDA_Report.pdf

## 📊 Power BI Dashboard
A two-page interactive dashboard was developed to support HR decision-making.

## 🔹 Page 1: Attrition Overview (WHAT)
- Total Employees
- Total Attrition
- Attrition Rate (%)
- Attrition by Gender, Department, Job Role, and Marital Status

## 🔹 Page 2: Attrition Drivers (WHY)
- Attrition vs Monthly Income
- Attrition vs Overtime
- Attrition vs Years at Company
- Attrition vs Years Since Last Promotion
- Attrition vs Distance From Home
- Attrition vs Job Satisfaction

📷 Dashboard screenshots:
Dashboard_Page1.png
Dashboard_Page2.png

## 💡 Key Insights
- Attrition is higher among early-career and lower-paid employees
- Employees working overtime show significantly higher attrition
- Delayed promotions and low job satisfaction strongly influence exits
- Longer commute distance contributes to higher attrition
- Senior roles and long-tenure employees show stronger retention

## ✅ Business Impact
- This analysis helps HR teams:
- Identify high-risk employee segments
- Understand root causes of attrition
- Monitor attrition KPIs effectively
- Support retention and workforce planning decisions

  ## 📁 Repository Files

| File Name | Description |
|----------|-------------|
| `HR_Employee_Attrition.csv` | Raw HR employee attrition dataset (CSV format) |
| `HR_Attrition_EDA.ipynb` | Python notebook for data cleaning and exploratory data analysis |
| `HR_Attrition_EDA_Report.pdf` | Detailed EDA report with visualizations and insights |
| `HR_Attrition_Dashboard.pbix` | Interactive Power BI dashboard file |
| `Dashboard_Page1.png` | Power BI dashboard – Attrition overview page |
| `Dashboard_Page2.png` | Power BI dashboard – Attrition drivers analysis page |
| `Problem_Statement.md` | Business problem definition and project objectives |
| `README.md` | Project overview, methodology, and insights |


## 📌 Conclusion
This project demonstrates an end-to-end HR analytics workflow, from data exploration to dashboard-driven insights, enabling organizations to move from attrition monitoring to root-cause analysis.
