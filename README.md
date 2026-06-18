# Employee-Turnover-Dashboard-Power-BI

An end-to-end Power BI dashboard built to help the HR department at NOVA understand, analyze, and act on employee attrition trends across the organization.

### Problem Statement

NOVA's HR department lacked visibility into the patterns, root causes, and risk factors driving employee attrition (16.1%), making it difficult to identify at-risk employees, understand demographic and performance-related drivers, and take timely preventive action to reduce turnover and its associated costs.

### Project Overview

This project transforms raw HR data into an interactive analytics dashboard that enables data-driven retention strategies. The data was sourced from a custom-built MySQL database and modeled in Power BI using DAX to surface key attrition KPIs, demographic patterns, and high-risk employee segments.

### Data Preparation

1. Connected Power BI to MySQL using the built-in MySQL Server connector
2. Imported the fact_attrition table as the single source of truth
3. Validated and modeled the data for use across all report pages
4. Built custom DAX measures for KPIs, satisfaction scores, income comparisons, and risk segmentation

### DAX Measures

| Category | Measures |
| ---- | ----- |
| Core KPIs | Total Employees, Total Attrited, Attrition Rate, Retention Rate, Attrition Rate % |
| Income | Avg Monthly Income, Avg Income Attrited, Avg Income Retained | 
| Satisfaction & Engagement | Avg Job Satisfaction, Avg Work Life Balance, Avg Environment Satisfaction, Avg Job Involvement, Avg Tenure |
| Risk | High Risk Employees (low satisfaction + low work-life balance + currently employed) |

### Dashboard Pages

| Page | Description |
| -----| ---- |
| Overview | High-level attrition KPIs, trends by year, department, and job role |
| Demographics | Attrition breakdown by gender, age, marital status, education, and distance from home | 
| Performance | Satisfaction, work-life balance, and Key Influencers analysis for attrition drivers |
| Details | Employee-level drill-through table filtered by role, income, and risk status |

### Key Features


🎯 4-page interactive report with consistent NOVA branding

🔍 Drill-through navigation from summary visuals to employee-level detail

🧠 Key Influencers visual to automatically surface top attrition drivers

🎛️ Filter panel for dynamic slicing by department, job level, and performance rating

📊 15+ custom DAX measures powering all KPI cards and visuals



### Key Insights


Overall attrition rate stands at 16.1%, with 711 employees attrited out of 4,410

Research & Development and Sales Executive roles show the highest attrition rates

Employees with ≤1 year tenure are 2.7x more likely to attrit

Single marital status increases attrition likelihood by 2.18x

Low work-life balance (≤1) increases attrition likelihood by 2.06x

361 employees identified as high-risk based on low satisfaction and work-life balance scores


