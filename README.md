# Human Resources Employee Attrition & Retention Report

An executive HR analytics project evaluating workforce attrition drivers, compensation gaps, overtime impact, and statistical correlations across 1,470 employees to improve organizational retention strategies.

## 📌 Executive Overview
This repository contains a data-driven diagnostic of employee turnover. The analysis focuses on identifying key risk factors—such as salary disparities, workload burn-out (overtime), role-specific attrition, and tenure with current managers—providing strategic recommendations for talent retention.

## 📊 Key Findings & Metrics

### 🔑 Key Performance Indicators (KPIs)
* **Total Employees:** 1,470
* **Total Attrition:** 237 employees
* **Overall Attrition Rate:** 16.12%
* **Average Monthly Income (Stayed vs. Left):** $6,833 vs. $4,787 (**30% pay gap / -$2,046 difference**)

### 🚨 Critical Insights
* **Overtime Impact:** Employees working overtime experience a **30.5% attrition rate**, compared to only **10.4%** for those on standard schedules. Overtime attrition accounts for 8.64% of total company headcount loss.
* **Top At-Risk Roles:** Three operational roles account for **~70% of total attrition** (166 out of 237 departures):
  * **Laboratory Technician:** 62 departures
  * **Sales Executive:** 57 departures
  * **Research Scientist:** 47 departures
* **Compensation Gap:** Attrition is heavily concentrated in entry-level, low-compensation positions starting at $1,009/month. 80% of departures occur below the organizational median salary.

### 📈 Pearson Correlation Highlights
* **Attrition vs. Monthly Income ($r = -0.16$):** Lower compensation consistently correlates with higher turnover risk.
* **Attrition vs. Years with Current Manager ($r = -0.16$):** Early tenure under a direct manager (first 2 years) is the critical window for voluntary departure.
* **Attrition vs. Age ($r = -0.16$):** Younger employees exhibit a significantly higher turnover probability.
* **Age vs. Monthly Income ($r = +0.50$):** Strong positive correlation showing salary progression tied to tenure and experience.

## 🛠️ Stack & Tools Used
* **Data Processing & Analysis:** Microsoft Excel (Pivot Tables, Advanced Formulas, Statistical Correlation Matrix)
* **Visualization & Reporting:** Executive KPI Dashboards, Salary Dispersion Charts, and OverTime Breakdown
* **Documentation:** Markdown

## 💡 Strategic Recommendations
1. **Workload & Overtime Mitigation Policy:** Set monthly overtime caps and redistribute operational workloads.
2. **Competitive Salary Adjustments:** Revise entry-level pay scales and retention bonuses for Laboratory Technicians, Sales Executives, and Research Scientists.
3. **Managerial Onboarding & Mentorship:** Implement quarterly check-ins and leadership surveys during the critical first two years under a manager.

## 📁 Repository Structure
* `HR Employee Attrition - Laureano.xlsx`: Full Excel workbook containing executive summary, KPI dashboard, correlation matrix, and processed sheets.
* `README.md`: Repository overview and strategic takeaways.
