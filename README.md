# Fundraising-Performance-Insight
This analysis uncover insights that can inform future campaign planning and targeting.
## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Data Preparation](#data-preparation)
- [Data Analysis](#data-analysis)
- [Insights Findings](#insights-and-findings)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

### Project Overview
This data analysis project aims to provide insights into evaluating the performance of previous year campaign 

The goal is to identify key trends, understand factors influencing ROI, income and response rate, and make data-driven recommendations that can help improve fuure campaign  and overall best performance.

![Campaign 2022](https://github.com/user-attachments/assets/a5576f28-d602-4db1-bb33-b1cab395b739)

### Tools and Technologies Used
  - Power BI – For data visualization and report creation.
  - Power Query – For data transformation and cleaning.
  - DAX (Data Analysis Expressions) – For creating custom calculations and measures.
  - Excel – For initial data exploration.

### Data Preparation
1. Data Cleaning: Data has no missing values and duplicates, and data types was formatted using Power Query.
2. Data Transformation: Standardized column names, created calculated columns, and applied data normalization where necessary.

### Data Analysis 
Using DAX Measures & Calculations

Response rate
  ```
  ResponseRate = DIVIDE([CountContactReference], SUM('Segment Matrix'[Mailing Count]))
  ```
  - Calculates the response rate.
    
ROI
  ```
 ROI = ([TotalIncome] - SUM('Segment Matrix'[Segment Cost]))/SUM('Segment Matrix'[Segment Cost])
  ```
  - Calculate ROI

    
### Insights and Findings

- High Attrition in Life Sciences & Medical Educational Fields: Employees with backgrounds in Life Sciences and Medical education fields are more likely to leave the company, possibly due to job dissatisfaction or workload-related challenges.
- Impact of Age Band and Gender: Employees aged between 31-40, particularly males, have the highest attrition rate.
- Marital Status Influence: Single males exhibit a significantly higher attrition rate compared to divorced employees.

### Recommendations
Based on the analysis I would recommend the follwing actions:
- Continue prioritizing raffle-based appeals and expand them to more segments
- Reassess communication strategy for low-performing segments
- Run a Gift Aid declaration campaign targeting non-declared supporters

### Conclusion
  This Power BI report highlights key factors influencing fundraising and provides actionable insights. 

[Flaticons](https://www.flaticon.com/)

Thank you 🙂 
