# 📊 HR Analytics Dashboard and Sales Dashboard | Power BI

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
# 📊 Sales Performance Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive Sales Performance Dashboard built using Microsoft Power BI. The dashboard provides business stakeholders with valuable insights into sales performance, profitability, customer behavior, and product trends to support data-driven decision-making.

The objective of this project is to analyze historical sales data, identify business trends, monitor KPIs, and uncover opportunities to improve sales and profitability.

---

## 🎯 Business Problem

Businesses generate large volumes of sales data every day. However, without proper analysis, it becomes difficult to understand:

- Which products generate the highest revenue?
- Which regions perform the best?
- Which customers contribute the most sales?
- How do sales and profits change over time?
- What business strategies can improve profitability?

This dashboard answers these business questions through interactive visualizations.

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Microsoft Excel (Dataset)

---

## 📂 Dashboard Pages

### 1️⃣ Sales Performance Dashboard
- Total Sales
- Total Profit
- Total Orders
- Sales by Category
- Sales by Region
- Monthly Sales Trend
- Top Performing Products

### 2️⃣ Sales Trend & Forecast Dashboard
- Monthly Sales Trend
- Profit Trend
- Forecast Analysis
- Year-over-Year Performance
- Seasonal Sales Analysis

### 3️⃣ Exploratory Data Analysis (EDA)
- Category Distribution
- Customer Analysis
- Regional Performance
- Product Analysis
- Sales Distribution

---

## 📈 Key KPIs

- Total Sales
- Total Profit
- Profit Margin
- Total Orders
- Quantity Sold
- Average Order Value

---

## 📊 Business Insights

- Identified top-performing products contributing the highest revenue.
- Analyzed regional sales performance to identify high-growth markets.
- Monitored monthly sales trends to understand seasonal demand.
- Compared profit and sales across product categories.
- Evaluated customer purchasing patterns to identify valuable customers.

---

## 📌 Features

- Interactive Filters & Slicers
- Dynamic KPI Cards
- Drill-down Visualizations
- Forecast Analysis
- Interactive Charts
- Clean & User-Friendly Dashboard Design

---

## 📷 Dashboard Preview

> Add screenshots of each dashboard page here.

Example:

```
Dashboard_Images/
│── Sales Dashboard.png
│── Sales Trend Dashboard.png
│── EDA Dashboard.png
```

---

## 📁 Project Structure

```
Sales-Dashboard/
│
├── Sales Dashboard.pbix
├── Dataset.xlsx
├── Dashboard_Images/
├── README.md
└── Screenshots/
```

---

## 🚀 Skills Demonstrated

- Data Cleaning using Power Query
- Data Modeling
- DAX Measures
- Dashboard Design
- Data Visualization
- Business Intelligence
- Data Storytelling

---

## 📌 Future Improvements

- Add Customer Segmentation Analysis
- Implement Drill-through Pages
- Add Dynamic Tooltips
- Build Executive Dashboard
- Include Advanced DAX Measures (YTD, YoY, MoM Growth)
- Add Row-Level Security (RLS)

---



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


### Overview Dashboard

!

### Attrition Analysis

!

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

📧 Email: amulyakankipati1234@gmail.com

⭐ If you found this project useful, please consider giving it a star!
