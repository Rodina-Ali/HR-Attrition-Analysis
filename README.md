# HR-Attrition-Analysis

📁 Project Overview

Employee attrition poses a serious challenge to organizational performance and continuity. This project explores the patterns, causes, and predictors of employee turnover using a real HR dataset. The goal is to uncover actionable insights to support strategic HR planning and improve retention.

🗄️Data Structure
Rows: 1,471 employee records
Columns: 32 features including:

  - Demographics (Age, Gender, Marital Status)
  - Job details (Department, Job Role, Business Travel)
  - Compensation (Monthly Income, Job Level)
  - Work conditions (Distance from Home, Overtime, Work-Life Balance)
  - Satisfaction and engagement metrics
  - Attrition status

🎯 Objectives

   - Analyze the impact of demographic factors, work logistics, and job satisfaction on attrition
   - Identify high-risk employee segments
   - Provide data-driven recommendations to reduce attrition and improve employee retention

🧹 Data Cleaning (Excel)

  - Removed duplicates
  - Dropped irrelevant columns (EmployeeCount, Over18, StandardHours)
  - Confirmed absence of null values
Note: Dataset lacked timestamp data, limiting time-series analysis
See full cleaned dataset here

🧠 Data Analysis & Visualization (Power BI)

    Used Power BI to create interactive dashboards and visuals

    DAX (Data Analysis Expressions) was used to calculate custom metrics such as:

       - Attrition Rate by Age Group
       - Average Monthly Income by Department
       - Overtime vs. Attrition Percentage
       - Travel Frequency Impact on Attrition
       - Satisfaction Score Impact on Retention
       - Role-specific Attrition Ratios
    Created dynamic slicers for gender, job role, age group, income level, and more

🔑 Key Findings

    Age & Gender: Highest attrition among 18–25 age group, especially females (42%)
 <p align="center">
    <img src="Overall.png" width="500" height="300">
</p>
    Income Level: Low-income employees account for 43% of total attrition

    Distance from Work: Employees living "Very Far" had a 22% attrition rate

    Business Travel: Frequent travelers had the highest attrition (52%)

    Overtime: Employees working overtime had a 31% attrition rate vs. 10% for those who didn't

    Job Role: Sales Representatives experienced the highest attrition (40%)

    Satisfaction Scores: Lower job involvement (34%) and work-life balance (31%) strongly correlated with higher attrition

    Tenure: Highest attrition among employees with either 0–10 or 31+ years at the company

    
