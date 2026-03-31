# Human Resource Analysis
# Project Overview
This project analyzes employee attrition using the IBM HR Analytics dataset. The goal is to identify key drivers of employee turnover and provide actionable HR insights using Excel and Tableau.

# Business Objectives
The aim of this project is to identify the key drivers of employee attrition and deliver actionable retention recommendations to the Chief Human Resource Officer and Human Resource Business Partners.

# Data Source
The data used for this work is gotten from Kaggle- 
<https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset>

# Tools Used
Excel (Power Query, Formulas, PivotTables)
Tableau (Data Visualization & Dashboards)

# Dataset
1,470 employees
35 columns including demographics, job roles, compensation, and satisfaction metrics

# Data Preparation and Transformation
- Removed constant columns (EmployeeCount, Over18, StandardHours)
- Decoded categorical fields (Education, JobSatisfaction, WorkLifeBalance)
- Created calculated columns:
  - Attrition Flag (0/1)
  - Age Band, Income Band, Tenure Band
  - Retention Risk Score
  - Risk Category (High, Medium, Low)
  - Compensation Ratio

# Excel Analysis
- Attrition rate by Department and Job Role
- Overtime impact on attrition
- Gender pay gap analysis
- Income and tenure distribution
- Promotion stagnation analysis
- Interactive PivotTables with slicers

# Data Visualization
I moved the excel file to Tableau where I created 12 worksheets and 3 dashboards

# Tableau Dashboards
1. HR Executive Summary
- KPIs
- Attrition rate overview
- Attrition by department, age band and job role

<img width="1619" height="810" alt="image" src="https://github.com/user-attachments/assets/61a3f9fd-1b4a-4652-a942-bb2bcfd37a1e" />

2. Compensation & Performance
- Salary distribution
- Gender pay comparison
- Compensation vs attrition analysis

<img width="1641" height="810" alt="image" src="https://github.com/user-attachments/assets/3aaae466-f721-4856-86a2-8269f2e2539e" />

3. Attrition Risk Intelligence
- Risk category segmentation
- Overtime vs attrition
- Satisfaction heatmap
- High-risk employee identification

<img width="1518" height="829" alt="image" src="https://github.com/user-attachments/assets/8f07abfe-65d9-49c8-803a-e9af60221af3" />

# Key Insights
- Sales and HR typically show higher attrition rates than R&D which indicates role pressure, targets, or job instability. 
- Employees in 0–2 years tenure band show the highest attrition. This means that there is onboarding or expectation mismatch. 
- While employees working overtime have significantly higher attrition rates, employees with low Job Satisfaction and Work Life Balance leave more and employees with low Compensation Ratio (<1) show higher attrition.
- High-risk category aligns strongly with actual attrition. 

# Business Recommendations
- Retention strategies should be focused on high-turnover departments.
- There is need to improve onboarding, mentorship, and early engagement programs and monitor workload
- Flexible work policies should be introduced to reduce burnout risk and work-life balance policies should be improved.
- Conduct employee surveys and act on feedback.
- Compensation structures should be adjusted. This could be done through benchmarking salaries against market rates.
- There is need to create clearer career progression paths and increase internal mobility opportunities 
- Pay equity should be ensured and regular compensation audits conducted.

# Project Outcome
This project demonstrates end-to-end data analysis:

- Data cleaning and transformation
- Exploratory data analysis
- KPI development
- Dashboard design and storytelling

# Notes
This project is part of a data analytics portfolio demonstrating HR analytics and business intelligence skills.

# Thank you for reading.
I am open to data analyst role.
