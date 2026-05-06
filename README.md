# IBM HR Analytics Dashboard Project

## Overview  
This project focuses on designing and developing interactive HR dashboards to improve visibility into workforce performance, employee retention, and compensation efficiency.

The objective was to transform structured HR data into actionable insights for different stakeholders within the organization. Three dashboards were created, each tailored to a specific user group: executives, the employee retention team, and the compensation team.

---

## Objectives  
- Provide a clear view of workforce effectiveness and organizational stability  
- Identify key factors contributing to employee attrition  
- Monitor and optimize compensation-related costs  
- Support data-driven HR decision-making  

---

## Data Preparation  
- Removed anomalies where employee count was less than or equal to 15  
- Cleaned missing and inconsistent values  
- Structured the dataset for accurate KPI calculations  
- Ensured consistency across all dashboards  

---

## Dashboard 1: Executive Overview  

### Purpose  
Designed for senior leadership (CEO, CFO, COO) to monitor overall workforce performance and long-term business stability.

### Key Metrics  
- Revenue per Employee  
- Attrition Rate  
- Cost of Hiring  
- Average Workforce Age  
- Gender Distribution  

### Key Insights  
- Evaluation of workforce productivity and efficiency  
- Analysis of hiring costs relative to business output  
- Gender representation across departments  
- Department-level workforce trends  

---

## Dashboard 2: Employee Retention Analysis  

### Purpose  
Developed for the retention team to analyze employee turnover and improve retention strategies.

### Key Metrics  
- Percentage of Employees Leaving  
- Average Staff Turnover Cost  
- Profit per Employee  
- New Hire Retention Rate  

### Key Insights  
- Attrition patterns across age groups and demographics  
- Financial impact of employee turnover  
- Effectiveness of new hire retention  
- Identification of factors influencing employee exits  

---

## Dashboard 3: Compensation and Cost Analysis  

### Purpose  
Built for the compensation team to manage salary expenses and ensure cost efficiency.

### Key Metrics  
- Compensation Cost as Percentage of Revenue  
- Year-on-Year Salary Increase  
- Payroll Error Percentage  
- Average Daily Travel Cost per Employee  
- Employee Overtime Percentage  

### Key Insights  
- Salary distribution across departments  
- Trends in compensation growth  
- Overtime contribution to overall costs  
- Financial efficiency of compensation strategies  

---

## Business Context  

- Revenue (2021): 5,735 Cr USD  
- Operational Expenses: 56% of revenue  
- Expense Distribution:  
  - HR: 11%  
  - R&D: 67%  
  - Sales: 22%  
- Average Daily Commute Cost: 0.625 USD per mile  

---

## Tools and Technologies  
- Microsoft Excel (Pivot Tables, Slicers, Dashboarding)  
- Data Cleaning and Transformation  
- Data Visualization  

---

## Visual Overview  

```text
                HR DATASET (CLEANED)
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
 Executive Dashboard   Retention       Compensation
   (CXOs View)         Dashboard        Dashboard
        │                │                │
        ▼                ▼                ▼
 Workforce KPIs     Attrition Insights   Cost Analysis
        │                │                │
        └────────────── Insights & Decisions ──────────────┘