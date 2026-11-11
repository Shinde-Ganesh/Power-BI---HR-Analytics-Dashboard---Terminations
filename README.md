# Power-BI---HR-Analytics-Dashboard---Terminations


Power Bi Dashboard from Raw Data for HR Analytics - Terminations

An interactive HR Analytics Power BI Dashboard designed to analyze employee attrition patterns, demographic factors, salary distribution, and tenure trends among terminated employees across departments.

**Dashboard Screenshot**

<img width="1232" height="702" alt="image" src="https://github.com/user-attachments/assets/70c64d1b-17a4-4c89-866d-317c8e465244" />


**Project Overview**

Understanding employee turnover is crucial for improving workplace culture, optimizing hiring strategies, and retaining top talent. This dashboard provides HR leaders and decision-makers with detailed insights into voluntary and involuntary employee exits.

**Key business questions addressed:**

  * What is the current attrition rate across departments?
  * How does employee turnover vary by age, salary tier, and tenure?
  * Which job roles suffer from the highest attrition rates?
  * How do education background and gender intersect with employee departures?

**Executive Summary & Key Insights**

  * Total Workforce Evaluated: 1,470 Employees
  * Total Attrition Count: 237 Terminated Employees
  * Overall Attrition Rate: 16.12%
  * Average Employee Age: 37 Years
  * Average Monthly Salary: $6.5K
  * Average Tenure: 7.0 Years

 Primary Attrition Drivers:

  * Tenure Peak:   Highest spike in attrition occurs around Year 1 (59 departures), tapering off as tenure increases.
  * Age Bracket:   The 26–35 age group experiences the highest attrition (116 employees).
  * Salary Impact:   Lower salary tiers (Upto $5k) account for the majority of terminations (163 employees).
  * High-Risk Roles:   Laboratory Technician (62), Sales Executive (57), and Research Scientist (47) account for the highest total exits.


**Data Model & DAX Measures**

Key DAX measures developed in Power BI for this analysis:
  *  Total Employees
  *  Total Attrition
  *  Attrition Rate
  *  Average Age
  *  Average Salary
  *  Average Tenure


**Dashboard Layout & Visualizations**

The report features a clean dark mode UI paired with high-contrast color highlights:

Executive Key Performance Indicators (KPI Cards): - 
  * Real-time metrics for Count of Employee, Attrition, Attrition Rate, Avg Age, Avg Salary, and Avg Tenure.

Departmental Slicers: - 
  * Quick-toggle filters for Human Resources, Research & Development, and Sales.

Demographic & Behavioral Breakdown: - 
  * Attrition by Gender: Card split comparing male vs. female attrition counts.
  * Attrition by Education: Donut chart detailing attrition percentage by education stream.
  * Attrition by Tenure: Line/Area graph mapping employee turnover across years at company (0 to 10+ years).
  * Job Role & Satisfaction Matrix: Matrix grid listing job roles evaluated across job satisfaction/performance scales (1 to 4).
  * Attrition by Salary Slab: Horizontal bar chart categorizing attrition across salary brackets (Upto 5k, 5k-10k, 10k-15k, 15k+).
  * Attrition by Age Group: Bar chart segmenting departures by age brackets (18–25, 26–35, 36–45, 46–55, 55+).
  * Attrition by Job Role: Summary bar chart highlighting top roles impacted by turnover.


**Tools & Technologies Used**

Business Intelligence: Microsoft Power BI Desktop

Data Transformation: Power Query (M Language)

Calculations & Analytics: - Data Analysis Expressions (DAX)


