📊 HR Data Analysis: SQL & Power BI Portfolio Project
🌟 Project Overview
This project features a comprehensive end-to-end data analysis workflow. I managed and cleaned a large-scale Human Resources dataset containing over 22,000 employee records using MySQL, then developed an interactive dashboard in Power BI to visualize workforce demographics, turnover rates, and hiring trends.

🛠️ Tech Stack
Database: MySQL Workbench

Visualization: Power BI

Language: T-SQL / MySQL

🚀 Data Cleaning & Transformation
The raw data required extensive preprocessing to ensure accuracy for the final report:

Date Standardization: Implemented CASE statements and STR_TO_DATE functions to resolve inconsistent formatting in birth dates, hire dates, and termination dates.

Feature Engineering: Created a calculated age column using the TIMESTAMP DIFF function to enable age-group distribution analysis.

Data Validation: Filtered out logical inconsistencies, such as records with future dates or employees listed under the age of 18.

Type Conversion: Modified column data types from strings to proper date objects to facilitate time-series analysis.

🔍 Key Business Questions Answered
Workforce Demographics: What is the gender and race/ethnicity breakdown across the organization?

Turnover Analysis: Which departments have the highest turnover rates, and what is the average length of employment for staff?

Retention & Tenure: How has the net employee count changed over the last 20 years (2000–2020)?

Work Environment: How many employees are based at headquarters versus working remotely?

📂 Project Structure
/SQL_Queries/: All scripts used for data cleaning, table modification, and exploratory queries.

/PowerBI_Dashboard/: The interactive .pbix file containing the multi-page HR report.

/Documentation/: Screenshots of the dashboard and a summary of the analytical findings.
