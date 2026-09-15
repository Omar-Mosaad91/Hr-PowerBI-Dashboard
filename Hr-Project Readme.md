# 📊 IBM HR Analytics Dashboard — Power BI Project

## 📊 Project Overview

A comprehensive, multi-page interactive **Power BI dashboard** built to analyze workforce dynamics, employee turnover, compensation structures, and career progression using the IBM HR Analytics dataset.

This project transforms raw HR data into clear, descriptive insights to help management understand workforce distribution, why employees leave, how compensation is structured, and what factors drive career milestones.

---

## 🎯 Project Objectives

- **Analyze Workforce Demographics:** Evaluate total employees, gender distribution, marital status, and department breakdowns.
- **Investigate Attrition Trends:** Identify high-risk segments based on age, job role, salary range, and department turnover.
- **Evaluate Compensation & Performance:** Assess salary distribution across departments and job levels alongside performance ratings and satisfaction levels.
- **Track Career Growth:** Explore employee tenure, promotion gaps, and training metrics.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query** — Data Cleaning & Transformation
- **DAX** — Measures & Calculations
- **Data Visualization** — Interactive cross-filtering, KPIs, custom cards, and multi-page layout

---

## 📑 Dashboard Pages & Descriptive Analysis

### 1. 🏠 Overview Page
The **Overview** page acts as the primary entry point, providing a high-level executive summary of the organization's overall workforce metrics.
* **Key Metrics:** Tracks **1,470 Total Employees**, an **Attrition Count of 237** (**16% Attrition Rate**), and an **Average Salary of 7K**.
* **Descriptive Insights:** 
  * *Department & Education:* Highlights that Research & Development holds the highest volume of employees (961), while Life Sciences and Medical fields dominate educational backgrounds.
  * *Demographics:* Shows workforce distribution by gender (60% Male vs. 40% Female) and marital status (led by Married employees at 673).

Screenshot/Over View.png

---

### 2. 🚶‍♂️ Attrition Analysis
The **Attrition Analysis** page performs a deep dive into the demographic and behavioral factors driving employee resignations.
* **Descriptive Insights:** 
  * *Age & Turnover:* The highest concentration of departures occurs within the **26–35** age group (116 employees).
  * *Role Breakdown:* **Laboratory Technicians** and **Sales Executives** record the highest attrition counts.
  * *Salary & Overtime:* Lower compensation tiers experience sharper attrition percentages, and employees working overtime show a massive turnover propensity.
  * *Department Share:* Research & Development leads in total attrition count (56.12%) due to its sheer workforce size.

![Attr Analysis](Screenshots/Attr%20Analysis.png)

---

### 3. 💰 Salary & Performance
The **Salary & Performance** page evaluates financial compensation structures, job levels, and employee evaluations across the organization.
* **Descriptive Insights:** 
  * *Income Distribution:* Research & Development absorbs the largest share of total monthly income compared to Sales and Human Resources, with an overall average monthly income of **6.50K** and a **15%** average salary hike.
  * *Job Level Scaling:* Average salaries scale progressively across the 5 structural job levels, reaching up to $19.2K at executive tiers.
  * *Performance & Satisfaction:* Tracks performance ratings per department alongside employee satisfaction levels distributed across Very High (459), High (442), Low (289), and Medium (280) brackets.

![Salary](Screenshots/Salary.png)

---

### 4. 📈 Employee & Career
The **Employee & Career** page focuses on employee longevity, promotion timelines, training investments, and long-term career paths.
* **Descriptive Insights:** 
  * *Tenure & Working Years:* Visualizes the distribution of total working years (averaging **11 years**) and years spent at the company (averaging **7 years**), alongside an average age of **37**.
  * *Promotion Bottlenecks:* Analyzes the "Time Since Last Promotion" to flag employees stuck in career stagnation.
  * *Training Frequency:* Tracks average training times across departments (averaging **3 training times**) to measure continuous learning investments.

![Employee](Screenshots/Employee.png)

---

## 🧠 Skills Demonstrated

- HR Data Analytics & Business Intelligence
- Exploratory Data Analysis (EDA)
- Data Cleaning & Transformation (Power Query)
- Advanced DAX Modeling & Measures
- KPI Development & Report Layout Design
- Descriptive Data Storytelling

---

## 📂 Repository Structure

```text
IBM-HR-Analytics-Dashboard/
│
├── IBM_HR_Analytics.pbix
├── README.md
│
└── Screenshots/
    ├── Over%20View.png
    ├── Attr%20Analysis.png
    ├── Salary.png
    └── Employee.png

## 🚀 How to Use

1. Download the `.pbix` file.
2. Open it using **Power BI Desktop**.
3. Start from the **Over View** landing page.
4. Use the navigation buttons to explore the dashboard.
5. Interact with the slicers and visuals to analyze the data.

---

## 👤 Author

**Omar Mosaad**

Data Analyst | Power BI | Excel | Python
