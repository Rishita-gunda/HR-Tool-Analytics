# 📊 Power BI Dashboard – HR Analytics 

## 🏢 Introduction

The HR Analytics Dashboard is a comprehensive Power BI report designed to help HR professionals visualize and analyze workforce data effectively.
It provides key insights into headcount, retention, and turnover metrics — enabling organizations to make data-driven decisions about employee engagement, workforce planning, and organizational health.

This project simplifies HR reporting through interactive visualizations, making it easier to identify trends, uncover insights, and take actionable steps to improve retention and reduce turnover.

## 📁 Dataset

- Source:  Excel CSV files

### 📊 Data Model Design

- *Fact Table*:
  - people_fact
    
- *Dimension Tables*:
  
  - department_dim

  - job_level_dim

  - term_dim

  - manager_dim

  - demographic_dim

  - education_dim

  - location_dim

  - marital_dim
  

---

## 🖥️ Dashboard Overview

This project consists of *4 pages*, each targeting specific business objectives:


### 1. 📌 1. Cover Page

#### 🔧 Design Highlights:
Serves as the introduction and navigation hub of the dashboard.
Summarizes the purpose and benefits of the report.

Provides clickable navigation cards to access:

🧍‍♂️ Headcount Page

🔁 Retention Page

🔻 Turnover Page

---

### 2. 👥 2. Headcount Analysis

#### Displays total employee headcount for a selected timeframe.

Key breakdowns include:

🏢 By Department – Departments with the most employees.

🧱 By Job Level – From Individual Contributor to CEO.

⚧ By Gender, Age, Race & Ethnicity – Workforce diversity analysis.

🎓 By Education Level – Academic background distribution.

💍 By Marital Status – Single vs Married employees.

📍 By Location – On-site vs Remote work distribution.

🗺️ By City – Cities with the highest headcount, shown on a map.

⏳ Dynamic timeframe slicer for flexible year-based filtering.

🖱️ Interactive tooltips for quick drill-down insights.

---

### 3. 🔁 3. Employee Retention

#### Focuses on employee retention performance across years, departments, and job levels.

Allows users to select a timeframe using a year range slicer (e.g., 2013–2019).

Provides insights from multiple perspectives:

📅 Retention by Year – Tracks how retention rates evolve over time.

🧑‍💼 Retention by Job Level – Shows variation in retention across hierarchy levels (Manager, Team Lead, Individual Contributor).

🏢 Retention by Department – Identifies which departments have strong or weak retention performance.

Empowers HR professionals to monitor engagement, evaluate retention strategies, and pinpoint areas for improvement.

---

### 4.🔻 4. Employee Turnover

#### Visualizes turnover rates (%) by year, department, and job level.

Displays key metrics:

📊 Turnover Percentage

🧮 Departing Employees Count

👥 Average Number of Employees

Includes a detailed Departing Employee Table:

🧾 Employee Name

📅 Termination Date

🏢 Department

💰 Salary

Termination Analysis:

⚖️ By Type: Voluntary vs Involuntary separations

💼 By Reason: Better opportunity, salary, performance, or personal reasons

📈 Year-over-year trend chart shows workforce stability over time.

---

## ✅ Conclusion

The HR Analytics Power BI Dashboard provides a powerful, data-driven view of workforce dynamics — offering clear visibility into headcount, retention, and turnover trends.
By leveraging interactive visuals and KPI-driven insights, HR teams can:

📊 Monitor workforce composition and growth.

🔁 Identify departments or job levels with high retention or turnover.

💡 Uncover demographic patterns influencing employee engagement.

🧭 Make informed, strategic decisions to improve employee satisfaction and retention.

This dashboard transforms raw HR data into actionable intelligence, helping organizations optimize workforce planning, reduce attrition, and build a stronger, more engaged workforce.

---

## 🛠️ Tools & Technologies


💻 Tool: Power BI Desktop

📂 Data Source: Excel / CSV HR dataset

---
## 🧮 Techniques & Methods:

Data Modeling (Star Schema)

DAX Calculations for KPIs and measures

Interactive Visualization Design

---
## 📊 Visual Types Used:

Bar & Column Charts

Donut Charts

Line Charts

KPI Cards

Maps

Histograms









































