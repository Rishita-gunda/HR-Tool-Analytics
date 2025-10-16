📊 HR Analytics Power BI Dashboard
🧾 Project Overview

The HR Analytics Dashboard is a comprehensive Power BI report designed to help HR professionals visualize and analyze workforce data effectively.
It provides key insights into headcount, retention, and turnover metrics — enabling organizations to make data-driven decisions about employee engagement, workforce planning, and organizational health.

This project simplifies HR reporting through interactive visualizations, making it easier to identify trends, uncover insights, and take actionable steps to improve retention and reduce turnover.

🚀 Key Features
🧩 1. Cover Page

Serves as the introduction and navigation hub of the dashboard.

Summarizes the purpose and benefits of the report.

Provides clickable navigation cards to access:

🧍‍♂️ Headcount Page

🔁 Retention Page

🔻 Turnover Page

Designed with a professional orange-gray theme for clarity and consistency.

👥 2. Headcount Analysis

Displays total employee headcount for a selected timeframe.

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

🔁 3. Employee Retention

Focuses on employee retention performance across years, departments, and job levels.

Allows users to select a timeframe using a year range slicer (e.g., 2013–2019).

Provides insights from multiple perspectives:

📅 Retention by Year – Tracks how retention rates evolve over time.

🧑‍💼 Retention by Job Level – Shows variation in retention across hierarchy levels (Manager, Team Lead, Individual Contributor).

🏢 Retention by Department – Identifies which departments have strong or weak retention performance.

Empowers HR professionals to monitor engagement, evaluate retention strategies, and pinpoint areas for improvement.

🔻 4. Employee Turnover

Visualizes turnover rates (%) by year, department, and job level.

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

🧠 Data Model

The Power BI model is structured using a star schema, integrating multiple dimension and fact tables for efficient analytics.

🗂️ Table Name	📘 Description
people_fact	Central fact table containing employee-level data
date	Time dimension table for period-based filtering
department_dim	Department reference and hierarchy
demographic_dim	Demographic details (gender, race, age group, etc.)
education_dim	Education background data
job_level_dim	Job hierarchy levels
manager_dim	Manager and reporting details
location_dim	Work location and geographic data
marital_dim	Marital status reference
term_dim	Termination types and reasons
parameter	Parameter table for dynamic slicers and visuals
🛠️ Tools & Technologies

💻 Tool: Power BI Desktop

📂 Data Source: Excel / CSV HR dataset

🧮 Techniques & Methods:

Data Modeling (Star Schema)

DAX Calculations for KPIs and measures

Interactive Visualization Design

📊 Visual Types Used:

Bar & Column Charts

Donut Charts

Line Charts

KPI Cards

Maps

Histograms

📈 KPIs & Metrics
KPI	Description
👥 Total Headcount	Total number of active employees
📊 Headcount Growth Rate	Change in headcount over time
🔁 Employee Retention Rate	Percentage of employees retained
🔻 Employee Turnover Rate	Percentage of employees who left
⚖️ Voluntary vs Involuntary Termination	Breakdown of exit types
🏢 Department-wise Headcount & Retention	HR metrics by department
🌎 Diversity Metrics	Distribution by gender, age, race, and education
🎨 Design Highlights

🧡 Clean, business-oriented layout with consistent typography and color scheme.

🖼️ Orange and gray theme ensures readability and visual harmony.

🧭 Interactive navigation for seamless page transitions.

🎛️ Built-in filters and slicers enhance data exploration.

👩‍💼 Tailored for HR professionals, analysts, and executives.
