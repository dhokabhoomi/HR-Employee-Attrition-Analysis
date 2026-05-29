# HR Employee Attrition Analysis

## Overview

This project performs **Exploratory Data Analysis (EDA)** on the **IBM HR Employee Attrition Dataset** to identify patterns and factors influencing employee turnover.

The objective is to understand why employees leave the organization and uncover trends related to **age, work-life balance, education, commuting distance, salary, and promotions**.

## Problem Statement

Employee attrition is a major challenge for organizations as it impacts productivity, hiring costs, and team stability.

This analysis aims to answer questions such as:

- Which employees are more likely to leave?
- Does age influence attrition?
- Is work-life balance related to employee retention?
- Does commuting distance affect turnover?
- How do education level and salary relate to attrition?
- Are promotions helping employee retention?

## Dataset Information

The dataset contains **1,470 employee records** with **35 features**, including:

| Feature | Description |
|----------|-------------|
| Age | Employee age |
| Department | Employee department |
| MonthlyIncome | Monthly salary |
| WorkLifeBalance | Work-life balance rating |
| DistanceFromHome | Distance travelled to office |
| Education | Education level |
| YearsSinceLastPromotion | Years since last promotion |
| Attrition | Employee left company or not |

## Technologies Used

- **Python**
- **Pandas** – Data Cleaning & Analysis  
- **Matplotlib** – Data Visualization  
- **Seaborn** – Statistical Visualization  
- **Jupyter Notebook**

## Exploratory Data Analysis

The project explores employee attrition through multiple visualizations and trend analysis.

### Age vs Attrition
Employees who left the organization tend to be **younger on average**, suggesting early-career professionals may switch jobs more frequently for better opportunities or career growth.

### Work-Life Balance vs Attrition
Employees with **lower work-life balance scores** show slightly higher attrition, indicating employee well-being may influence retention.

### Distance From Home vs Attrition
Employees with **longer commuting distances**, especially in the **HR department**, exhibit relatively higher attrition, suggesting travel burden may impact retention.

### Education & Income vs Attrition
Attrition is observed across all education levels, though **highly educated employees may still leave**, possibly due to expectations for better compensation and career advancement.

### Years Since Last Promotion vs Attrition
Employees who left tend to have **fewer years since their last promotion**, indicating promotions alone may not guarantee long-term retention.

## Key Insights

- Younger employees are more likely to leave the organization.
- Work-life balance plays an important role in employee retention.
- Long commuting distances may contribute to attrition.
- Higher education does not necessarily ensure retention.
- Promotions alone are insufficient for improving long-term employee retention.
