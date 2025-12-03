
# HR Employee Attrition Analysis

## Python Data Analysis Project

This repository contains a full data analysis project focused on understanding **employee attrition**, its root causes, and actionable HR insights to improve retention.
The analysis was conducted in a Jupyter Notebook (Python_Final_Project2.ipynb) and visualized through dashboard using multiple KPI

---

## Project Structure

├── Python_Final_Project2.ipynb - Full analysis notebook (EDA, KPIs, insights) <br>
├── README.md - Project documentation (this file) <br>
├── images - All generated plots (.png) <br>
├── Python Final Project.csv - HR dataset used in the analysis <br>
├── Dashboard - Tableau dashboard <br>

---

## Project Objective

The goal of this project is to:
* Identify key factors contributing to employee attrition.

* Analyze relationships between satisfaction, compensation, performance, and turnover.

* Calculate HR-focused KPIs.

* Build visualizations and insights for decision-makers.

* Provide data-driven recommendations to reduce attrition.

---

## Dataset Overview

The dataset contains:

* 1,470 employees

* 36 features, including:

   * Demographics: Age, Gender, Marital Status, Education
   * Job details: Job Role, Department, Job Level, Years at Company
   * Compensation: Monthly Income, Stock Options, Salary Hike
   * Satisfaction metrics: Job Satisfaction, Environment Satisfaction, Work-Life Balance
   * Commute: Distance From Home
   * Performance rating
   * Attrition (Yes/No)

   ---

## Analysis Steps

1. **Data Loading & Cleaning**:
   * Imported dataset using Pandas
   * Checked missing values (none found)
   * Created calculated fields

2. **Exploratory Data Analysis (EDA)**:
   * Visualized distributions of income, distance, tenure
   * Cross-tabulation of attrition by demographics and departments
   * Correlation heatmap to identify strongest relationships

3. **KPI Evaluation**: <br>
   Based on the project guidelines, the following KPIs were analyzed:
   1. Attrition Trends & Patterns
   2. Compensation & Benefits Analysis
   3. Work-Life Balance & Satisfaction
   4. Career Growth & Job Stability
   5. Geographic & Commuting Factors

---

## Key Visual Insights (Dashboard Highlights)

Below is a sample from the dashboard included in this project, showcasing major KPIs and charts:


### KPI 1: **Attrition Trends and Patterns (by attrition rate)**

Below are several graphs that together provide a comprehensive overview of attrition trends and patterns:

**Attrition Concentration Across Tenure Groups**

   ![Attrition_Rate_by_Tenure_Group_graph.png](images/Attrition_Rate_by_Tenure_Group_graph.png)

---

### KPI 2: **Compensation and Benefits Analysis**

**Average Monthly Income by Department**

![Average_Monthly_Income_by_Department_(Employees_Who_Left_vs._Stayed)_graph.png](images/Average_Monthly_Income_by_Department_(Employees_Who_Left_vs._Stayed)_graph.png)

---

### KPI 3: **Work-Life Balance and Satisfaction:**

**Attrition Analysis by Satisfaction and Balance Factors**

![Attrition_Analysis_by_Satisfaction_and_Balance_Factors_graph.png](images/Attrition_Analysis_by_Satisfaction_and_Balance_Factors_graph.png)

---

### KPI 4: **Career Growth and Job Stability**

**Attrition Rate by Job Level (%)**

![Attrition_Rate_by_Job_Level_graph.png](images/Attrition_Rate_by_Job_Level_graph.png)

---

### KPI 5: **Geographic and Commuting Factors**

**Attrition Rate (%) by Distance Group**

![Attrition_Rate_Percent_by_Distance_Group_graph.png](images/Attrition_Rate_Percent_by_Distance_Group_graph.png)

---

## Summary of Findings

From the analysis, several important patterns were identified:

   * Low Work-Life Balance correlates with higher attrition.
   * Employees with lower salaries tend to leave more frequently.
   * Attrition is significantly higher among employees with short tenure (0–2 years).
   * Job roles such as Sales Representative show higher turnover compared to others.
   * Longer commute distances increase the likelihood of leaving.

---

## Recommendations

Based on the findings:

   1. **Improve Work-Life Balance** <br>
      Introduce hybrid models, flexible hours, and promote healthy workload practices.

   2. **Review Compensation Structure** <br>
      Evaluate and update salary ranges, especially for lower job levels. 
   
   3. **Support New Employees** <br>
      Strengthen onboarding and mentorship programs in the first 1–2 years.
   
   4. **Analyze High-Turnover Job Roles** <br>
      Examine roles with high attrition to identify workload or role-related issues.

   5. **Provide partial remote-work flexibility for employees with long commutes** <br>
      This can significantly reduce attrition for far-distance employees.

   6. **Create Clear Career Growth Paths** <br>
      Define transparent promotion criteria and growth opportunities so employees know how they can advance within the organization.


By implementing these strategies, HR can reduce attrition, improve employee satisfaction, and foster long-term organizational success.

---

## Authors:
Ofir Ben-Harush, Tal Ezra, Neta Shtayer, Zvi Fuchs, Yelena Zamansky Glazer, Tehila Hamdi <br>
Python | SQL | Tableau

