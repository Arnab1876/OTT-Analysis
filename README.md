# User Login Behavior – OTT Streaming Analytics Case Study

This project analyzes user login and engagement behavior on an OTT (Over-the-Top) streaming platform using realistic synthetic data. It uncovers insights into churn, retention, technical performance, and promotional effectiveness through SQL and data visualization.

## Overview

- **Timeframe**: Jan 2023 – Mar 2024 (15 months)
- **Tools Used**:  
  - SQL (BigQuery)  
  - Google Looker Studio  
  - Google Sheets & Excel
  - Figma
  
- **Skills Applied**:  
  - Root Cause Analysis  
  - Window Functions & CTEs  
  - Cohort & Segmentation Analysis  
  - DAU/MAU, Churn & Retention Metrics  
  - Dashboarding & Storytelling

## Dataset

This is a synthetic dataset generated using generative AI for learning and portfolio purposes.

### Tables

- **Viewers**: signup date, country, age group  
- **Logins**: date, device type, login channel, session score  
- **Sessions**: timestamps, success/failure, duration  
- **Promotions**: promo types, dates, discounts

Dataset links:
- [viewers.csv](https://github.com/Arnab1876/OTT-Analysis/blob/main/viewers.csv)
- [logins.csv](https://github.com/Arnab1876/OTT-Analysis/blob/main/logins.csv)
- [sessions.csv](https://github.com/Arnab1876/OTT-Analysis/blob/main/sessions.csv)
- [promotions.csv](https://github.com/Arnab1876/OTT-Analysis/blob/main/promotions.csv)

## Key SQL Queries & Use Cases

| Use Case | SQL Query |
|----------|-----------|
| Daily & Monthly Active Users (DAU/MAU Trends) | [DAU](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query1.sql) · [MAU](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query4.sql) |
| Detect Inactive Users | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query2.sql) |
| Weekly Engaged Users (3+ days/week) | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query3.sql) |
| Avg. Session Duration by Region & Age | [Region](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query5.sql) · [Age Group](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query6.sql) |
| Time from Signup to Last Login | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query7.sql) |
| First Login Drop-off | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query8.sql) |
| Login Channel vs. Retention | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query9.sql) |
| Trial Users: Retention & Activity | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query13.sql) |
| Promotion vs. Organic Viewer Sessions | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query14.sql) |
| Signup Cohort Retention | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query12.sql) |
| Viewer Churn by Country | [Query](https://github.com/Arnab1876/OTT-Analysis/blob/main/Query17.sql) |


## Dashboard & Visualizations

Built using Looker Studio:

- [Live Dashboard](https://lookerstudio.google.com/u/0/reporting/b142085d-ce40-470e-82ea-d555ca43d3f4/page/p_rc75fgeutd)
- [PDF Summary Report](https://github.com/Arnab1876/OTT-Analysis/blob/main/OTT_User_Activity_-_Visualization.pdf)

Included:
- DAU & MAU Trends
- Viewer Distribution by Age, Country, Acquisition Type
- Promo Strategy vs Retention & Session Success
- Region-wise Engagement Patterns

