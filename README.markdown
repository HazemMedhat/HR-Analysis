# HR Data Analysis Project

## Overview
This project contains HR data for a company, stored in an Excel file (`Hazem Medhat Project.xlsx`). The dataset includes detailed employee information and various pivot tables summarizing key metrics. This README provides an overview of the data structure, its contents, and potential uses for analysis.

## Dataset Description
The dataset is organized into multiple sheets within the Excel file, each serving a specific purpose. Below is a summary of each sheet:

### 1. HR_Table
This sheet contains detailed employee records with the following columns:
- **Company**: Company identifier (1 or 2).
- **Employee Number**: Unique identifier for each employee.
- **Employee Name**: Name of the employee.
- **Gender**: Male or Female.
- **Age**: Current age of the employee.
- **Branch**: Department or division (e.g., Civil Projects, Marine Projects, Office).
- **Cost Center**: Numeric code for cost allocation.
- **Hire Date**: Date of hire (in Excel date format).
- **Age When Entered The Company**: Age at the time of hiring.
- **Finish Date**: Date of employment termination (if applicable).
- **Hire Year/Month**: Year and month of hire.
- **Finish Year/Month**: Year and month of termination (if applicable).
- **Employment Status**: Active, Vacation, or Left.
- **Contract Leave**: Number of leave days.
- **Nationality**: Employee's nationality (e.g., Pakistan, Egypt, Saudi Arabia).
- **Job Title**: Role or position (e.g., Carpenter, Safety Officer, Civil Engineer).
- **Total Salary Package**: Total compensation including allowances.
- **Basic Salary**: Base salary.
- **Allowances**: Food, Housing, Transportation, Travel, Medical, Vacation, Other Earnings.
- **Last Increment**: Most recent salary increment.
- **Accrued Amount**: Accumulated financial obligations.
- **Total Cost**: Total cost to the company (salary + accrued amount).

**Sample Data**:
- Employee: MUHAMMAD, Male, 60, Painter, Pakistan, Total Salary: 1250, Basic Salary: 830, Total Cost: 2619.66.
- Employee: LAYLA, Female, 38, Administrator, Saudi Arabia, Total Salary: 4000, Basic Salary: 2600, Total Cost: 4996.92.

### 2. Employees Dashboard
This sheet is a placeholder for an employee dashboard.

### 3. Cost and Salary Dashboard
This sheet is a placeholder for a cost and salary dashboard.

### 4. KPIs Pivot Table
Summarizes key performance indicators:
- **Total Employees**: 2072
- **Number of Left Employees**: 178
- **Employment Status**:
  - Active: 1507
  - Vacation: 387
  - Left: 178
- **Distinct Nationalities**: 25
- **Distinct Job Titles**: 231
- **Total Salary Package**: 8,005,792
- **Average Basic Salary**: 2455.79
- **Total Last Increment**: 597,528
- **Net Cost**: 11,588,593.91
- **Attrition Rate**: 8.59%

### 5. Overview Pivot Table
Provides data on employee attrition by month and year:
- **By Month**: Highest attrition in April (49 employees) and March (41 employees).
- **By Year**: Highest attrition in 2014 (446 employees) and 2015 (229 employees).

### 6. Company Pivot Table
Breaks down data by company:
- **Company 1**: 1755 employees, 178 left, 7 branches, 215 job titles, Total Cost: 8,951,918.50.
- **Company 2**: 317 employees, 7 branches, 83 job titles, Total Cost: 2,636,675.41.

### 7. Nationality Pivot Table
Summarizes employee data by nationality:
- **Top Nationalities**: Pakistan (679), India (674), Saudi Arabia (255).
- **Left Employees**: Pakistan (77), India (67).
- **Average Basic Salary**: Ghana (2700), India (1508.88), Pakistan (1303.98).
- **Average Age When Entered**: USA (61), Somalia (57).

### 8. Job Title Pivot Table
Summarizes data by job title:
- **Top Roles**: Carpenter (303), Steel Fixer (241), Administrator (140).
- **Top Costs**: Carpenter (819,048.89), Administrator (749,612.17).
- **Top Increments**: Managing Director (45,000), VP - Finance (22,500).

### 9. Branch Pivot Table
Breaks down data by branch:
- **Top Branches**: Civil Projects (1207 employees), Marine Projects (391), Office (225).
- **Total Costs**: Civil Projects (5,639,372.43), Office (2,373,047.90).
- **Average Age When Entered**: Alumco Projects (39.28), Marine Projects (33.75).

### 10. Gender Pivot Table
Summarizes data by gender:
- **Male**: 1986 employees, Average Basic Salary: 2428.24, Total Cost: 11,117,602.81.
- **Female**: 86 employees, Average Basic Salary: 3091.86, Total Cost: 470,991.10.

## Potential Analyses
This dataset can be used for various HR-related analyses, such as:
- **Attrition Analysis**: Identify patterns in employee turnover by year, month, nationality, or job title.
- **Cost Analysis**: Evaluate total costs by branch, job title, or nationality to optimize budget allocation.
- **Salary Distribution**: Analyze salary packages and increments across roles, genders, or branches.
- **Demographic Insights**: Study age, gender, and nationality distributions to inform diversity and inclusion strategies.
- **Retention Strategies**: Identify factors contributing to high attrition rates (e.g., low increments, specific branches).