# HR Employee Analytics Dashboard

Power BI dashboard project built on the IBM HR Employee Attrition dataset. The report analyzes workforce composition, employee attrition, salary patterns, job satisfaction, overtime, tenure, and department-level trends to help HR teams understand where employee loss is concentrated.

## Project Overview

This project uses Power BI to transform employee-level HR data into an interactive analytics dashboard. It focuses on identifying attrition patterns across departments, job roles, salary bands, age groups, overtime status, and tenure groups.

The dashboard is designed for HR managers, business analysts, and decision makers who need a quick view of employee retention risks and workforce distribution.

## Key Metrics

|Metric|Value|
|-|-:|
|Total Employees|1,470|
|Employees Left|237|
|Attrition Rate|16.1%|
|Average Monthly Income|INR 6.50K|

## Main Insights

* Research & Development has the highest number of employees and the highest attrition count.
* Laboratory Technicians, Sales Executives, and Research Scientists show the highest attrition by job role.
* Overtime is an important factor for attrition comparison, with the dashboard separating employees by overtime status.
* Salary, job satisfaction, tenure, age group, and department filters help explore workforce patterns in more detail.

## Dashboard Pages

### HR Analytics Dashboard

Shows executive KPI cards and department-level summaries, including:

* Total employees
* Employees left
* Attrition rate
* Average salary
* Average salary by department
* Average salary by job role
* Employees left by job role
* Employees left by department
* Employees left by overtime
* Total employees by age group
* Total employees by salary band

![HR Analytics Dashboard](Screenshot%201-1.png.jpeg)

![Dashboard Snapshot](Screenshot%201.png)

### Employee Details

Provides employee-level records and job role summaries, including:

* Employee number
* Department
* Job role
* Attrition status
* Average salary by job role
* Total employees by job satisfaction
* Total employees by company tenure group

![Employee Details](Screenshot%202.png)

### Job Role Analysis

Highlights job-role based totals and attrition distribution, including:

* Total working years by job role
* Years at company by job role
* Monthly income by job role
* Employees left by job role
* Job satisfaction distribution
* Overtime distribution

![Job Role Analysis](Screenshot%203.png)

## Files Included

|File|Description|
|-|-|
|`HR Employee Analytics by CoE.pbix`|Primary Power BI report file|
|`Power bi project COE 30.07.2026.pbix`|Alternate Power BI report file for the project|
|`WA_Fn-UseC_-HR-Employee-Attrition.csv`|Source HR employee attrition dataset|
|`HR Employee Analytics Dashboard Presentation.pptx`|Project presentation deck|
|`HR-Employee-Analytics-Dashboard.pptx`|Additional presentation file|
|`HR Employee Analytics.png`|Project title/banner image|
|`Screenshot 1-1.png.jpeg`|Dashboard overview page screenshot|
|`Screenshot 1.png`|Additional dashboard screenshot|
|`Screenshot 2.png`|Employee details page screenshot|
|`Screenshot 3.png`|Job role analysis page screenshot|

## Dataset Fields

The dataset contains employee demographic, compensation, job, performance, satisfaction, and tenure attributes, including:

* Age, gender, marital status, education, and education field
* Department, job role, job level, and business travel
* Monthly income, hourly rate, daily rate, and salary hike percentage
* Job satisfaction, environment satisfaction, relationship satisfaction, and work-life balance
* Overtime, training, years at company, years in current role, and years since last promotion
* Attrition status

## Tools Used

* Microsoft Power BI Desktop
* Power Query for data cleaning and transformation
* DAX measures for KPI calculations
* CSV dataset as the source file
* PowerPoint for project presentation

## How to Use

1. Open `HR Employee Analytics by CoE.pbix` or `Power bi project COE 30.07.2026.pbix` in Microsoft Power BI Desktop.
2. Confirm the CSV source path points to `WA_Fn-UseC_-HR-Employee-Attrition.csv`.
3. Refresh the data model if needed.
4. Use slicers such as Department and Employee Number to explore employee attrition patterns.
5. Review the screenshots or presentation deck for a quick project walkthrough.

## Recommended Improvements

* Fix the total employee KPI formatting if it displays as currency instead of a count.
* Add a dedicated attrition-risk summary page for high-risk job roles and departments.
* Include trend analysis if future time-based HR data becomes available.
* Add calculated measures for attrition rate by department, job role, overtime, and tenure group.

## Authors

Rudrashis Chowdhury, Gourab Mondal, and Tuhin Roy

