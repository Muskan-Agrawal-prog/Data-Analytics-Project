# Data-Analytics-Project
# Employee Performance & Salary Analysis 📊

##  Project Overview

This project analyzes an **Employee Performance & Salary dataset** using Python and popular data analysis and visualization libraries.

The goal is to clean the employee data, perform meaningful analysis, identify patterns, and create visualizations to understand employee salary, performance, attendance, satisfaction, and departmental trends.

##  Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

##  Project Workflow

### 1. Data Loading & Understanding

* Loaded the employee dataset
* Checked dataset shape and columns
* Examined data types
* Generated statistical summaries
* Checked missing values and duplicates

### 2. Data Cleaning

* Handled missing values
* Removed duplicate records
* Converted columns to appropriate data types
* Converted `Joining_Date` into datetime format

### 3. Data Analysis

Analyzed:

* Average salary
* Highest and lowest salary
* Average performance score
* Department-wise salary
* Employee count by department
* Department-wise performance
* Job-role salary and performance

### 4. Feature Engineering

Created new columns:

* `Age_Group`
* `Performance_Level`
* `Salary_Category`

Performance levels:

* **90+** → Excellent
* **80–89** → Good
* **Below 80** → Needs Improvement

Salary categories:

* **Below 40,000** → Low
* **40,000–60,000** → Medium
* **Above 60,000** → High

### 5. GroupBy Analysis

Used Pandas `groupby()` to analyze:

* Department-wise employee count
* Average salary by department
* Average performance by department
* Performance levels by department
* Salary categories by department
* Salary by job role
* Performance by job role

### 6. Data Visualization

#### Matplotlib

Created:

*  Bar Chart — Average Salary by Department
*  Line Chart — Average Performance by Department
*  Pie Chart — Employees by Department
*  Histogram — Salary Distribution

#### Seaborn

Created:

*  Countplot — Employees by Department
*  Barplot — Average Salary by Department
*  Boxplot — Salary Distribution by Department
*  Heatmap — Correlation Between Numerical Variables

### 7. Final Insights

The project answers questions such as:

* Which department has the highest average salary?
* Which department has the highest average performance?
* Is salary related to performance?
* Which employees need improvement?
* Which employees are excellent performers?
* Which job role has the highest average salary?
* Which job role has the highest average performance?
* Which salary category has the highest average performance?
* Which department has the highest satisfaction?
* Which department has the highest attendance?
* Which department has the highest overtime?

##  Dataset

The dataset contains employee information such as:

* Employee ID
* Name
* Age
* Gender
* Department
* Job Role
* Experience
* Salary
* Performance Score
* Attendance
* Projects Completed
* Overtime Hours
* Satisfaction Score
* Joining Date
* City

##  Project Objective

The main objective of this project is to practice **data cleaning, data manipulation, groupby operations, feature engineering, and data visualization** using Python.

This project demonstrates how raw employee data can be transformed into useful insights through data analysis.

##  Author

**Muskan Agrawal**

This project was created as part of my journey learning **Python, NumPy, Pandas, Matplotlib, and Seaborn**.
