# 📊 Quality Assurance & Employee Performance Dashboard (Power BI)

## 📌 Project Overview
This Power BI project presents an end-to-end Quality Assurance (QA) and Employee Performance analysis. It monitors work samples, defect rates, critical errors, and overall quality scores across supervisors, employees, and geographic locations.

## 🔑 Key Features & Technical Implementation

* **DAX Measures & KPIs:**
  * `Sampling%`: Ratio of sampled tasks over total tasks using `DIVIDE`.
  * `Defects%`: Percentage of defects relative to sample size.
  * `Fatal Errors%`: Percentage of critical errors relative to sample size.
  * `Quality Score`: Overall quality metric calculated as `1 - Defects%`.

* **Advanced Visualizations & Interactive Reporting:**
  * **KPI Cards & Gauges:** Real-time tracking of Total Tasks, Samples, Defects, Fatal Errors, and Overall Quality Score.
  * **Scatter Chart with Play Axis:** Dynamic visualization comparing Samples vs. Defects per Employee over time.
  * **Time-Series Analysis:** Area Chart displaying Fatal Errors monthly trend.
  * **Geographic Analysis:** Map visualization presenting Quality Score by work location.
  * **Supervisor Insights:** Donut Chart and Clustered Bar Charts analyzing Quality Score and Sampling rate per supervisor.
  * **Custom Report Tooltip:** Page tooltip (`EMP Tooltip`) showing detailed employee-level Quality Score upon hovering over visual data points.

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** Advanced data visualization, dynamic tooltips, and custom report canvas formatting.
* **DAX (Data Analysis Expressions):** Custom measures for operational QA metrics.
* **Power Query:** Data transformation and field structuring.
