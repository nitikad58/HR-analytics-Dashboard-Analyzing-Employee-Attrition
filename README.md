# HR Analytics Dashboard ![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Viz-yellow?logo=powerbi)

## 1. HR Analytics Dashboard: Analyzing Employee Attrition 
An interactive Power BI dashboard analyzing employee attrition patterns, demographic trends, and key workforce metrics. Developed as a learning project to master HR analytics in Power BI, this dashboard helps identify retention risks and informs data-driven workforce strategies.

## 2. Short Description
This project was my hands-on journey into building a complete, professional Power BI dashboard from scratch. Following a tutorial framework, I transformed raw HR data into actionable insights, focusing on understanding the "why" behind employee turnover. The dashboard examines attrition patterns across departments, age groups, education levels, and job roles, providing a powerful tool for any HR department.

## 3. Tech Stack
  <p>📊 Power BI Desktop: Used for data modeling, DAX, and visualization design.<br> 
     🔧 Power Query: Employed for data cleaning, transforming, and handling data quality issues (null values, inconsistencies).<br> 
     🧮 DAX: Created custom measures and calculated columns for metrics like Attrition Rate, Averages, and conditional logic.<br> 
     🎨 Data Visualization: Designed an intuitive and interactive report with cross-filtering and a cohesive theme.</p>

## 4. Data Source

Source: A synthetic HR dataset provided as part of a Power BI tutorial, simulating a realistic employee database.

Key Data Points Included:
  * Employee Demographics (Age, Gender, Education Field)
  * Job Attributes (Department, Job Role, Job Satisfaction)
  * Compensation & Benefits (Monthly Income, Stock Option Level)
  * Work Experience (Years at Company, Total Working Years)
  * Attrition Indicator (Flag for employees who left)

## 5. Key Features & Insights 🔑

### 5.1 Business Problem
This project addresses the universal HR challenge of retaining top talent. It aims to uncover the root causes of employee attrition by answering:
  * Which departments or job roles are most affected?
  * How do factors like salary, age, and tenure influence the decision to leave?
  * Is there a correlation between job satisfaction and attrition?

### 5.2 Dashboard Goals
  * Provide an at-a-glance view of key HR KPIs.
  * Enable drill-down analysis by any demographic or job-related dimension.
  * Visualize trends to identify high-risk employee segments.
  * Serve as a starting point for proactive retention strategies.

### 5.3 Walkthrough of Key Visuals
📊 Key Performance Indicators (Top Cards)
   * Employee Count: 1,470 employees
   * Attrition Rate: 16.1% (237 employees)
   * Average Age: 37 years
   * Average Salary: $6,500/month
   * Average Tenure: 7 years

👥 Gender Distribution (Treemap)
  * A quick visual breakdown of male vs. female employee distribution.

🎓 Attrition by Education (Doughnut Chart)
  * Reveals that employees from Life Sciences and Medical backgrounds have the highest attrition rates, suggesting a need for targeted engagement in these fields.

📈 Attrition by Age Group (Bar Chart)
  * A clear highlight of employees aged 26-35 being the most likely to leave (160 employees), pinpointing a critical career stage for retention efforts.

💼 Job Role & Satisfaction (Matrix Table)
  * Combines Job Role, Satisfaction Scores, and Attrition Count.
  * Shows that Laboratory Technicians and Sales Executives have the highest turnover, often with lower satisfaction scores.

💰 Attrition by Salary Slab (Horizontal Bar Chart)
  * The most striking insight: 163 of the 237 employees who left were in the lowest salary bracket (<$5K), strongly highlighting compensation as a primary factor.

⏳ Attrition by Tenure (Area Chart)
  * Identifies two key risk periods: the first year of employment (59 employees) and after the 5-year mark, crucial for planning onboarding programs and career development interventions.

### 5.4 Interactive Features
  * Department Filter: A slicer allows dynamic filtering of the entire dashboard for any department (e.g., Sales, R&D, HR).
  * Cross-Filtering: Clicking on any visual filter disables all the others, enabling deep-dive analysis.
  * Tooltips: Hover-over effects provide additional context and data points.

## 6. How to Use
  * Download the .pbix file from this repository.
  * Open it using Power BI Desktop.
  * Use the filter on the top left to analyze data for a specific department.
  * Click on any chart to cross-filter the entire dashboard. For example, click on the "26-35" age bar to see only the data for that group across all other visuals.
  * Hover over data points to see more detailed tooltips.

## 7. 📈 Learning Outcomes & Project Journey
This project was an incredible learning experience that took me from following instructions to truly understanding the process.

What I learned:
 * End-to-End Dashboard Development: From importing and cleaning data in Power Query to publishing a polished report.
 * DAX Formulas: Gained practical experience writing measures for critical business metrics.
 * Data Storytelling: Learned how to arrange visuals logically to guide the viewer to key insights.
 * Design Best Practices: Understood the importance of layout, color, and interactivity in report design.

## 8. Screenshot Preview
### 8.1 Main Dashboard Preview
![Main Dashboard Preview](https://github.com/nitikad58/HR-analytics-Dashboard-Analyzing-Employee-Attrition/blob/main/HR%20Analytics%20screenshot%201-%20main%20dashboard.png)

### 8.2 Filtered Dashboard Preview: HR Department
![Filtered Dashboard Preview: HR Department](https://github.com/nitikad58/HR-analytics-Dashboard-Analyzing-Employee-Attrition/blob/main/HR%20Analytics%20screenshot%202-%20Department%20filter(HR).png)

### 8.3 Filtered Dashboard Preview: R&D Department
![Filtered Dashboard Preview: R&D Department](https://github.com/nitikad58/HR-analytics-Dashboard-Analyzing-Employee-Attrition/blob/main/HR%20Analytics%20screenshot%203-%20Department%20filter(R%26D).png)

### 8.4 Filtered Dashboard Preview: Sales Department
![Filtered Dashboard Preview: Sales Department](https://github.com/nitikad58/HR-analytics-Dashboard-Analyzing-Employee-Attrition/blob/main/HR%20Analytics%20screenshot%204-%20Department%20filter(Sales).png)

### 8.5 Females in all Departments Dashboard Preview
![Females in all Departments Dashboard Preview](https://github.com/nitikad58/HR-analytics-Dashboard-Analyzing-Employee-Attrition/blob/main/HR%20Analytics%20screenshot%205%20-%20All%20Departments%20(females%20only).png)

## 9. Acknowledgments:
This project was built following a comprehensive tutorial by Rishabh on YouTube. The tutorial provided the foundational dataset and a guide on core HR analytics concepts in Power BI.

While the initial structure was guided, the deep dive into analysis, the final design customization, and the creation of this documentation are my own work. This project solidified my understanding of how to translate business questions into a functional data analysis tool.
