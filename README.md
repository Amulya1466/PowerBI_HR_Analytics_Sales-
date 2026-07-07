# 📊 HR Analytics Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive HR Analytics Dashboard built using Power BI to analyze employee attrition, workforce demographics, job satisfaction, and overall organizational performance. The dashboard enables HR professionals and business leaders to identify key trends, improve employee retention, and support data-driven decision-making.

---

## 🎯 Business Problem

Employee attrition can significantly impact an organization's productivity and hiring costs. This dashboard helps HR teams answer important business questions such as:

- what is the headcount by department ?
- What is the headcount by gender?
- what is the average salary by department?
- top 5 names with highest salary in India vs newzealand
- what is the headcount by rating
- rating according to the first letter of name
- comparision between India and New Zealand

---

## 📊 Dashboard Features

- Executive HR Overview
- Employee Attrition Analysis
- Department-wise Attrition
- Job Role Analysis
- Age Group Distribution
- Gender Distribution
- Education Field Analysis
- Monthly Income Analysis
- Job Satisfaction Rating
- Interactive Filters & Slicers
- KPI Cards

---

## 📈 Key Performance Indicators (KPIs)

- Total Employees
- Active Employees
- Employees Left
- Attrition Rate (%)
- Average Age
- Average Monthly Income
- Average Years at Company
- Average Job Satisfaction

---

## 🛠 Tools & Technologies Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Cleaning
- Data Visualization

---

## 📚 DAX Measures Used

Examples of measures used in this project include:

```DAX
Total Employees = COUNT(Employee[EmployeeID])

Employees Left =
CALCULATE(
    COUNT(Employee[EmployeeID]),
    Employee[Attrition] = "Yes"
)

Attrition Rate =
DIVIDE([Employees Left], [Total Employees],0)

Average Income =
AVERAGE(Employee[MonthlyIncome])
```

---

## 📂 Dataset Information

The dataset contains employee information including:

- Employee ID
- Age
- Gender
- Department
- Job Role
- Education Field
- Monthly Income
- Years at Company
- Job Satisfaction
- Attrition Status
- Business Travel
- Marital Status
- Overtime

---

## 💡 Business Insights

Some insights obtained from the dashboard include:

- Sales department experienced the highest employee attrition.
- Employees working overtime showed a higher likelihood of leaving.
- Most attrition occurred among employees aged 26–35.
- Lower monthly income correlated with higher attrition.
- Employees with lower job satisfaction had increased turnover rates.

---

## 📸 Dashboard Preview

> Add screenshots of your dashboard below.

### Overview Dashboard

![Overview](Dashboard1.png)

### Attrition Analysis

![Attrition](Dashboard2.png)

---

## 📁 Repository Structure

```
PowerBI-HR-Analytics
│
├── HR_Analytics.pbix
├── HR_Analytics.csv
├── Dashboard1.png
├── Dashboard2.png
├── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open **HR_Analytics.pbix** using Microsoft Power BI Desktop.
3. Refresh the data if required.
4. Interact with the slicers and visuals to explore HR insights.

---

## 📌 Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX Measures
- Power Query
- Dashboard Design
- Business Intelligence
- Data Visualization
- KPI Reporting
- HR Analytics

---

## 📖 Project Outcome

This dashboard transforms raw HR data into meaningful business insights that help organizations understand workforce trends, monitor employee attrition, and make informed HR decisions through interactive visualizations.

---

## 👩‍💻 About Me

**Amulya Kankipati**

Aspiring Data Analyst passionate about transforming raw data into actionable insights.

### Skills

- Microsoft Excel
- SQL
- Power BI
- DAX
- Power Query
- Data Visualization
- Business Intelligence

📧 Email: your-email@example.com

🔗 LinkedIn: https://linkedin.com/in/your-profile

⭐ If you found this project useful, please consider giving it a star!
