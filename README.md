# Sales-Analytics-Dashboard-Regional-and-Departmental-Performance-Analysis-using-Power-BI

📁**Project Overview**

This repository contains a comprehensive Sales Analytics Dashboard project designed to provide actionable insights into company-wide sales performance. Using employee-level sales transaction data, the dashboard visualizes total sales, profit, commissions, regional and departmental breakdowns, target achievement, and workforce demographics. The dashboard supports business decision-making and resource optimization for sales-driven organizations.

📊**Dataset Description**

The dataset comprises detailed information for 50 employees, including columns for EmployeeID, Name, Age, Department, Region, SalesAmount, Target, TargetAchieved, CommissionPercentage, TotalEarnings, Age Group, and TotalCommission. Each row represents a unique employee’s contribution to sales and business results.

🎯**Key Questions & Objectives**

-	What are the trends in overall sales, profits, and commissions paid?
-	Which regions and departments perform strongest and weakest?
-	How is the workforce distributed by department and age group?
-	What proportion of employees reach or exceed their sales targets?
-	Are commission payouts effectively aligned with sales achievements?

🧹**Data Cleaning Process**

-	Deduplication: Ensured unique EmployeeID entries to prevent double counting.
-	Missing Value Handling: Validated completeness of all relevant fields. Imputed or flagged any missing or unusual values.
-	Categorical Standardization: Standardized department and region names for consistent grouping.
-	Numeric Validation: Checked for correct formatting, flagged outliers, and verified logical consistency (e.g., SalesAmount vs. TargetAchieved).
-	Consistency Checks: Cross-validated business logic (e.g., commission calculations, target achievements).

🔄**Data Transformation Steps**

-	Age Group Binning: Classified employees into age groups (18–25, 25–35, 35–45, 45–55) using Age column.
-	Aggregations: Summed sales and targets by region and department for performance analysis.
-	Commission Calculations: Computed TotalCommission for each employee based on CommissionPercentage and SalesAmount.
-	Target Achievement Flagging: Added binary indicators for whether targets were met or exceeded.
-	Employee Distribution: Counted employee totals by department and age group.

📈**Dashboard Features**

-	KPI Cards: Visual summary of total sales, net profit, total employees, commission paid, and target achievement.
-	Pie Charts: Sales breakdowns by region and by department.
-	Bar Charts:
-	Employee count by department.
-	Employee count by age group.
-	Target distribution and achievement rates by department.
-	Target vs. Achievement Analysis: Track which individuals and departments met sales targets.

💡**Business Insights**

-	The East region and Electronics department lead overall performance.
-	Majority workforce consists of experienced (45–55) and mid-career (25–35) employees.
-	Sales achievement aligns closely with commission payout, confirming effective compensation strategy.
-	Areas for expansion identified in underperforming regions/departments.

🛠️**Tools Used**

- 📊 Power BI: Dashboard creation and visualization.
- 🧠 DAX / M Language: Calculated columns, measures, logic modelling.

📈**Business Impact**

This project demonstrates robust data analytics and dashboarding skills for sales performance analysis. Its well-documented pipeline makes it an excellent addition to any analytics portfolio and provides value for businesses seeking to optimize their sales strategy and workforce performance.

