## HR Analytics: Attendance & Leave Pattern Analysis

### Project Overview
This project focuses on the analysis of employee attendance and leave patterns in order to help HR departments optimize resource allocation, plan for workforce requirements, and gain insights into the relationship between employee attendance and project performance. The dataset includes employee attendance records, which track various leave types such as Paid Leave, Sick Leave, Work from Home, and other specific leave categories like Birthday Leave, Floating Festival Leave, Bereavement Leave, and Menstrual Leave. The project uses advanced analytics techniques in Power BI and Tableau to create interactive dashboards and data visualizations that provide a clear view of employee attendance patterns and leave utilization.

### Objectives:
1. **Analyze Employee Attendance Patterns**: To gain insights into the trends of attendance, work-from-home behaviors, and leave usage across different employees.
2. **Optimize Resource Allocation**: By identifying trends in employee leave and attendance, HR can optimize resource planning and make informed decisions to prevent operational inefficiencies.
3. **Strategic Project Management**: Correlate attendance patterns with project engagement metrics to assess the impact of attendance on project timelines and productivity.
4. **Data-Driven Decision Making**: Leverage data visualizations to assist in HR decision-making, improve employee scheduling, and manage resource utilization effectively.

### Dataset:
The project utilizes an Excel-based dataset with the following columns:
- **AtliQ**: Unique identifier for each employee.
- **Employee Name**: The name of the employee.
- **Employee Code**: Unique employee code for tracking.
- **Days of the Month**: Columns representing the days of the month (e.g., 1st June, 2nd June, ..., 30th June).
- **Leave Types**: Various leave categories such as:
  - **Present**: Regular working days.
  - **Work from Home (WFH)**: Days when the employee worked from home.
  - **Paid Leave (PL)**: Days off with pay.
  - **Sick Leave (SL)**: Days off due to illness.
  - **Birthday Leave**: Leave taken for personal celebration.
  - **Floating Festival Leave**: Days off for festivals.
  - **Bereavement Leave**: Days off due to a family loss.
  - **Leave without Pay (LWP)**: Days taken off without pay.
  - **Weekly Off**: Employee’s weekly day off.
  - **Holidays Off**: Holidays taken by the employee.
  - **Menstrual Leave**: Leave specific to certain employees.
- **Total Present Days**: The total number of days the employee was present during the month.

### Key Features:
- **Power BI and Tableau Dashboards**: Using Power BI and Tableau, the project creates interactive dashboards that provide insights into attendance patterns, leave usage, and overall employee engagement. Dashboards include:
  - **Leave Utilization Insights**: A pie chart showing the percentage breakdown of various leave types (Paid Leave, Sick Leave, Work from Home, etc.).
  - **Attendance Trends**: A line graph or bar chart that tracks attendance trends over the course of the month. This helps HR departments identify peak attendance days or periods of absenteeism.
  - **Work-from-Home Insights**: Visualizations comparing the frequency of work-from-home days versus in-office attendance, helping to evaluate the impact of remote work on productivity.
  - **Employee-Level Performance Correlation**: A comparison of individual employee attendance records with their project engagement and performance metrics, helping to assess the impact of attendance on project success.
  
- **Trend Analysis and Predictive Insights**: By analyzing past attendance data, the dashboard can provide insights into potential future trends, helping HR anticipate peak attendance periods, resource shortages, or high leave requests.

### Insights and Examples:
1. **Leave Utilization Analysis**: One dashboard might display a **pie chart** breaking down the percentage of leave types used by employees, such as how many employees used paid leave versus sick leave.
2. **Attendance Trends**: A **line chart** could show the total attendance for each employee over the month, with spikes or dips in attendance visually highlighted. This helps HR identify patterns such as high absenteeism periods or low attendance during specific days.
3. **Work from Home**: A **bar graph** might compare the number of work-from-home days per employee against the number of in-office attendance days. This analysis can be crucial for understanding the impact of flexible work arrangements.
4. **Resource Planning**: Using the trends from the dashboard, HR managers can plan staffing needs based on historical data of when certain leave types are most commonly taken.

### Technologies Used:
- **Power BI**: Used to create interactive, user-friendly dashboards and visualizations. Power BI’s data manipulation and aggregation features were utilized to efficiently analyze large sets of employee attendance and leave data.
- **Excel**: The dataset was initially in Excel format, and extensive use of Excel functions (such as SUM, AVERAGE, COUNTIF) was used for data cleaning and preprocessing before importing it into Power BI/Tableau.

### How It Works:
1. **Data Preprocessing**: The raw Excel data is cleaned by ensuring that all employee records are properly formatted, and missing data is handled appropriately.
2. **Data Import**: Once cleaned, the data is imported into Power BI/Tableau for analysis and visualization.
3. **Building Visualizations**: Dashboards are created by selecting relevant KPIs, designing charts that represent employee leave data, and setting up interactivity features that allow users to drill down into specific details.
4. **Insights Extraction**: The dashboards allow HR managers to extract insights regarding employee attendance, leave patterns, and the correlation with project metrics.
5. **Decision Support**: These insights can be used by HR managers to make strategic decisions on workforce allocation, project planning, and resource management.

### Significance:
This project provides an easy-to-understand, data-driven approach to managing employee attendance and leave. The interactive dashboards offer HR professionals a powerful tool for optimizing workforce management. By correlating leave data with employee performance, organizations can ensure that they make better decisions regarding staffing and project allocation. Additionally, it aids in identifying trends such as increased absenteeism during specific periods and helps HR departments create more effective employee policies.

### Future Enhancements:
1. **Predictive Analytics**: Integrating machine learning models to predict future absenteeism trends based on historical data.
2. **Employee Engagement Correlation**: Enhancing the analysis by linking attendance and leave data with employee satisfaction and performance metrics.
3. **Automated Reporting**: Setting up automated reports to send HR updates on attendance and leave utilization trends at regular intervals.

### Conclusion:
The HR Analytics project using Power BI provides a comprehensive, visually appealing, and data-driven method for HR departments to understand employee attendance and leave trends. By leveraging the insights generated from the dashboards, organizations can make more informed decisions on staffing, resource allocation, and strategic planning, ensuring better operational efficiency.
