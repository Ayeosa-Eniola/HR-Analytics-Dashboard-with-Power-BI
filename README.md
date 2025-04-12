# Human Resources Analysis Project - Power BI
## Table of Content
[Project Overview](#project-overview)

[Purpose of the Analysis](#purpose-of-the-analysis)

[Analytical Objectives](#analytical-objectives)

[Dataset Description](#dataset-description)

[Tools](#tools)

[Data Preparation Process](#data-preparation-process)

[Key Analysis Performed](#key-analysis-performed)

[Insights and Interpretation](#insights-and-interpretation)

[Recommendations](#recommendations)

[Conclusion](#conclusion)

## Project Overview

This repository presents an in-depth Human Resources (HR) data analysis project conducted using Power BI. The primary purpose of this project is to apply advanced data analytics techniques to real-world HR data in order to identify critical organizational trends, challenges, and opportunities. It serves as a case study in how data analytics can be used to support evidence-based decision-making in workforce management, talent retention, and operational optimization.

Human capital is the most valuable asset of any organization. However, understanding employee behavior, performance, and attrition through raw data alone can be complex. This project addresses that gap by transforming raw HR data into meaningful, business-relevant insights. The analysis goes beyond simple visualization; it provides diagnostic and strategic interpretation of key HR metrics using a combination of Power Query for data cleaning, DAX for analytical modeling, and Power BI for structured reporting.

---

## Purpose of the Analysis

The core objective of this HR analysis is to derive actionable insights from employee data that can be used to support human resource planning and decision-making. This includes identifying root causes of employee attrition, measuring the effectiveness of training and development programs, understanding the relationship between job satisfaction and performance, and evaluating workforce demographics in the context of organizational goals.

Rather than relying solely on visual storytelling, this analysis places emphasis on the analytical process and the insights derived through business logic and quantitative exploration. By synthesizing relationships across variables such as job role, department, tenure, gender, education, and satisfaction level, the project presents a holistic view of workforce dynamics.

---

## Analytical Objectives

The analysis was guided by the following data-driven objectives:

1. **Identify and Quantify Attrition Patterns**  
   Analyze the distribution of employee attrition across departments, job roles, gender, and years at the company to uncover which segments of the workforce are most at risk of leaving and why.

2. **Evaluate Job Satisfaction Across Employee Segments**  
   Understand how job satisfaction varies across departments, genders, and tenure levels. Identify whether satisfaction is a leading indicator of turnover.

3. **Analyze the Impact of Training on Retention and Performance**  
   Measure whether the number of training hours employees receive has a quantifiable impact on performance ratings and attrition likelihood.

4. **Understand Performance Trends Over Time**  
   Evaluate how performance ratings vary by length of employment and department, and identify departments where long-term employees show declining performance.

5. **Assess Workforce Demographics and Equity**  
   Examine the age, gender, and educational background of employees across roles and departments to evaluate representation, diversity, and succession planning risks.

6. **Develop Insight-Driven Recommendations**  
   Translate findings into concrete strategies and recommendations that can be used by HR leadership to improve retention, satisfaction, performance, and equity.

---

## Dataset Description

The dataset used in this project consists of employee records from a hypothetical medium-to-large organization. Each row represents an individual employee, and the dataset includes variables such as:

- Employee ID
- Department
- Job Role
- Gender
- Age
- Education Level
- Years at Company
- Job Satisfaction (Score 1-5)
- Performance Rating
- Training Hours
- Attrition Status

The data was originally provided in Excel format and loaded into Power BI for cleaning, transformation, and modeling.

---

## Tools 

The following tools and techniques were applied throughout the lifecycle of the analysis:

| Tool                 | Purpose                                                                 |
|----------------------|-------------------------------------------------------------------------|
| **Power BI Desktop** | Core platform used for data modeling, analysis, and report creation.    |
| **Power Query**      | Used for data transformation, including filtering, renaming, and typing.|
| **DAX (Data Analysis Expressions)** | Used for creating calculated measures and columns to support deep analysis. |
| **Excel**            | Source format of the raw dataset.                                       |
| **Data Modeling**    | Relationships established between key fields to enable slice-and-dice.  |

---

## Data Preparation Process

Before any analysis was performed, the dataset was carefully cleaned and prepared. Data preparation included:

- **Column Renaming:** For clarity and consistency, columns were renamed to be intuitive and self-explanatory.
- **Data Type Correction:** Each column was formatted correctly (e.g., text, whole number, decimal).
- **Creation of New Columns:** Several calculated columns were added to support analysis (e.g., "Length of Employment", "Attrition Flag").
- **Missing Value Handling:** Fields with missing or null values were examined and treated appropriately.
- **Establishment of Relationships:** The dataset was modeled with appropriate relationships to enable cross-filtering across reports.

---

## Key Analysis Performed

**1. Attrition Behavior Analysis**

- Calculated the overall attrition rate.
- Analyzed attrition distribution by department, job role, and gender.
- Found that the highest attrition occurred among younger employees and those with 0–2 years at the company.
- Departments such as Sales and HR experienced the most significant turnover.

**2. Satisfaction and Engagement Levels**

- Measured average job satisfaction across departments and roles.
- Identified that employees in R&D had the highest satisfaction, while HR had below-average satisfaction.
- Found a strong correlation between low satisfaction scores and early exits.

**3. Training and Development Analysis**

- Compared average training hours between employees who stayed and those who left.
- Employees with more than 15 hours of training showed higher performance ratings and lower attrition.
- Suggested that underinvestment in training may contribute to dissatisfaction and turnover.

**4. Performance Distribution**

- Evaluated how performance ratings vary by tenure and job role.
- Discovered that mid-level employees (3–6 years) tend to have the highest ratings.
- Long-tenured employees sometimes exhibited stagnant or declining performance.

**5. Demographic Evaluation**

- Analyzed workforce by gender and age group.
- Highlighted underrepresentation of women in technical roles and leadership.
- Identified generational gaps in key departments, signaling a potential succession issue.

---

## Insights and Interpretation
From the analysis conducted, the following insights were drawn:

1. **High Attrition in Early Years:**
Employees in their first two years are significantly more likely to leave, emphasizing the need for strong onboarding and support during the early stages of employment.

2. **Job Satisfaction is Predictive:**
Low satisfaction scores are a strong predictor of attrition. Departments with low satisfaction tend to have high turnover rates.

3. **Training Matters:**
There is a clear relationship between training hours and retention/performance. Employees with low training exposure tend to perform worse and leave earlier.

4. **Performance Trends Vary by Tenure:**
Performance ratings peak in the mid-career stage, with some decline seen in long-tenured employees, possibly due to stagnation or lack of motivation.

5. **Equity Gaps Exist:**
Certain departments lack diversity in terms of gender or age, suggesting that targeted recruitment or internal promotion policies may be needed.

---

## Recommendations

Based on my findings, the following data-backed recommendations are proposed:

1. Enhance Onboarding Programs
Provide more structured support and mentorship to new employees to reduce early attrition.

2. Increase Targeted Training
Align training programs with employee needs, particularly in departments with high turnover or low satisfaction.

3. Introduce Continuous Feedback Mechanisms
Establish real-time satisfaction tracking through pulse surveys and manager feedback loops.

4. Re-evaluate Long-Term Roles
Implement career development plans and rotation programs for long-tenured employees at risk of performance stagnation.

5. Promote Diversity and Inclusion
Audit departmental hiring and promotion practices to ensure balanced representation across gender and age groups.

---

## Conclusion
This HR analysis project illustrates the transformative power of data when used strategically. Rather than merely visualizing information, the analysis interprets employee data to uncover real organizational challenges. By combining statistical reasoning with business understanding, this project provides HR professionals and stakeholders with the tools to make smarter, evidence-backed decisions.

It is my hope that this analysis not only demonstrates technical skills but also reflects the strategic thinking required to be an effective data analyst in the modern business environment.

