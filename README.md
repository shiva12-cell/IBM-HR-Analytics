# Adecco India HR Analytics & Attrition Analysis
Excel & Data Verification Project
An end-to-end data analytics and verification project examining employee attrition drivers at Adecco India. This repository contains the HR dataset, diagnostic analytical findings, and strategic recommendations to improve employee retention.
---
## Executive Summary
Employee attrition directly impacts organizational stability, productivity, and hiring costs. This project evaluates an enterprise HR dataset of **1,470 employees** across 35 attributes at Adecco India to identify primary attrition risk factors and validate retention findings against transactional HR records.
### Key Metrics Summary
* **Total Workforce:** 1,470 employees
* **Total Attrition Count:** 237 employees
* **Overall Attrition Rate:** **16.12%**
* **Average Monthly Income:** **$6,502.93** (~$6.5K)
* **Average Employee Age:** **36.92 years** (~36.9)
* **Workforce Gender Split:** 60.00% Male (882) / 40.00% Female (588)
---
## Repository Structure
```
.
├── WA_Fn-UseC_-HR-Employee-Attrition.csv  # HR Analytics Dataset & Analysis (1,470 rows x 35 columns)
├── TEMPLATE_FORMAT.md                    # Standardized Portfolio Template Format
└── README.md                             # Project Documentation & Findings
```
---
## Key Attrition Drivers & Deep Insights
### 1. Age & Career Stage Vulnerability
* Exited employees average **33.61 years of age**, nearly 4 years younger than retained peers (**37.56 years**), confirming heightened flight risk among early-career talent.
* **Single employees** exhibit an attrition rate of **25.53%** (120 of 470), more than double that of married (**12.48%**) and divorced (**10.09%**) colleagues.
### 2. Income Compensation & Equity Factors
* Departing employees earn an average of **$4,787.09/month**, earning **-$2,045.65 less (-29.9%)** than retained counterparts (**$6,832.74/month**).
* Employees with **no stock options (Level 0)** face a **24.41%** attrition rate. Granting baseline equity (**Level 1**) cuts attrition down to **9.40%**—a **61.5% turnover reduction**.
### 3. Workload & Overtime Stress
* Regular **Overtime** is the **#1 overall flight driver** ($r = +0.2461$). Employees working regular overtime experience an elevated turnover rate of **~30.50%** compared to standard-hours staff.
* Lower job involvement sharply multiplies turnover: employees with **Low involvement (Level 1)** suffer **33.73%** attrition, compared to **9.03%** for **Level 4 (Very High)**.
### 4. Department & Role Disparities
* The **Sales Department** has the highest overall attrition rate at **20.63%** (84 of 446), followed by **Human Resources (19.05%)** and **R&D (13.84%)**.
* **Sales Representatives** face extreme early-career attrition (~39.80%), while **Human Resources personnel** report the lowest job satisfaction across the company (**2.56 / 4.00**).
### 5. Commute Friction & Training Engagement
* Commute distance acts as a major risk multiplier: employees commuting **>20 km** face an attrition rate of **22.81%**, a >50% increase compared to employees living within 5 km (**14.08%**).
* Zero professional training sessions in a year leads to **27.78%** attrition, whereas providing 5–6 formal training sessions reduces turnover to **9.23%**.
---
## Strategic Recommendations for HR Leadership
1. **Junior Sales Compensation Restructuring:**
   * Adjust baseline salaries for junior Sales Representatives from ~$4,700 toward a $5,500 threshold to reduce dependency on volatile sales commissions.
2. **Overtime Governance & Workload Relief:**
   * Institute a manager approval cap for monthly overtime exceeding 15 hours, backed by mandatory compensatory time-off (comp-offs) to curb burnout.
3. **Broad-Based Micro-Vesting Equity (ESOP):**
   * Extend Level 1 micro-equity grants with 3-year cliff vesting to junior technical and sales contributors to capture the proven 61.5% retention benefit.
4. **Commute Relief & Hybrid Work Flexibility:**
   * Implement a 2-day remote working arrangement for staff commuting >15 km to eliminate daily travel friction and stabilize retention.
