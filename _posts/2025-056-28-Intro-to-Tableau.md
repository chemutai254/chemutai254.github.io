---
title: " Introduction to Tableau Public"
date: 2025-06-28
categories: [data-science]
tags: [data, analytics, data-science, machine-learning, artificial-intelligence]
---

# Human Resources Dashboard

## About the Project
This project aims at analyzing and visualizing a dashboard that will be used by the HR department to make decisions.
The dataset was obtained from the following link but customized to the Kenyan context:
![Link](https://www.datawithbaraa.com/tableau/tableau-hr-project-thank-you/)
The dataset consisted of the following 15 features:
1. employee_id
2. first_name
3. last_name
4. gender
5. state
6. city
7. hiredate
8. department
9. job_title
10. education_level
11. salary
12. performance_rating
13. overtime
14. birthdate
15. termdate

## Objectives
The project aims at:
1.	Understanding the business and client needs
2.	Loading Data
3.	Transforming Data
4.	Creating Calculated Measures
5.	Visualizing Dashboard
6.	Publishing the project 


# Project Execution
## Data Loading and Transformation
The dataset was loaded into Tableau by connecting the .csv dataset as shown below. The dataset was customized to the `Kenyan` context. 
![Connect](../assets/images/HR_Dashboard/Connect_to_Data.png) 

The data was transformed whereby the properties were adjusted.
![Properties](../assets/images/HR_Dashboard/File_properties.png)

The colors were customized for the entire workbook.
![Custom](../assets/images/HR_Dashboard/Custom_workbook.png)

The data was transformed by mapping 15 branches to their states.
![Branches](../assets/images/HR_Dashboard/Map_Branches_Cities.png)


## Calculated Measures
The following calculated measures were created: `Total Hired`, `Total Terminated`, `Total Active`, `% Total Hired`, `% Total Terminated`, `Age`, among others.
![Measures](../assets/images/HR_Dashboard/Calculated_Measures.png)

Relationships between `department` and `job title`, and among `Location`, `State`, and `Cities` were created.
![Relationships](../assets/images/HR_Dashboard/Relationship.png)

## Building Visualizations
### Summary of the employees hired by year
![Hired](../assets/images/HR_Dashboard/Hired_by_Year.png)
`2025` recorded the highest number of employees hired, 1,548 contributing to 17% compared to `2021` which recorded the lowest hiring numbers of up to 457, accounting for 5%.

### The number of employees terminated by year
![Terminated](../assets/images/HR_Dashboard/Terminated_by_Year.png)
`2024` recorded the highest number of employees terminated, 197 contributing to 20% termination rate. `2016` being the lowest recorded 1% termination rate with 7 employees being terminated.  
 
### Summary of employees hired and terminated by department.
![Department](../assets/images/HR_Dashboard/Hired_Term_Dept.png)
The green color represents the hired and pink the terminated.

### The total number of employees by job title.
![Job_Title](../assets/images/HR_Dashboard/Hired_Job_Title.png)
The employees in green represents job titles with majority of the employees.

### The total number of employees by State
![State](../assets/images/HR_Dashboard/By_State.png)
Nairobi consists of the highest number of employees compared to other states.

### The total number of employees by location.
![Location](../assets/images/HR_Dashboard/By_Location.png)
The `Headquarter` (Nairobi) consisted of 70% employees.

### Map showing location of the branches.
![Map](../assets/images/HR_Dashboard/Map.png)
The blue bubble indicates the `Headquarter` while the pink shows `Branches` in different states. Also, the bubble size increases and decreases depending on the number of employees in a location. 

### The percentage of active, hired, and terminated employees by gender
![Gender](../assets/images/HR_Dashboard/Gender.png)
Color green represents the percentage of hired employees while color pink, the percentage of terminated employees by `Gender`. The middle circle represents the percentage of the employees of a particular gender. 

### Heatmap showing Education level by age
![Education](../assets/images/HR_Dashboard/Education.png)
Employees with bachelor’s degree and within the age of between 34 to 44 contributed to 19% and the highest among the rest.

### The total number of employees by age
![Age](../assets/images/HR_Dashboard/Age.png)
The employees between ages 35 and 44 contributed to 31% of employees in the organization.

### The total number of employees by education level
![Education_Level](../assets/images/HR_Dashboard/Education_Level.png) 
The highest number of employees hired have bachelors’ degree.

### Employee performance by education level
![Performance](../assets/images/HR_Dashboard/Performance.png) 
Employees with masters were rated good in terms of performance contributing to 51%.

### Heatmap on education level by gender and salary
![Education_Salary](../assets/images/HR_Dashboard/Gender_Edu.png) 
Employees with PhD were paid the highest salaries.

### Scatterplot of salary versus department
![Salary](../assets/images/HR_Dashboard/Salary.png) 
Finance managers were the highest paid employees compared to other job roles.

## Summary Dashboards
The following is the summary of my findings:
### HR Summary Dashboard
![Dashboard](../assets/images/HR_Dashboard/HR_Dashboard.png)

### HR Details
![Details](../assets/images/HR_Dashboard/HR_Details.png) 

## Conclusion
To sum up, the number of active, hired and terminated employees were 7,950, 8,950, and 1000 respectively. The operations department contributed to the highest number of employees hired i.e. 2,417 and terminated i.e. 301 compared to the rest. The project was published on Tableau Public as seen in the link below:
https://public.tableau.com/app/profile/nancy.chemutai/viz/HRSummaryDashboard_17505277057340/HRSummaryDashboard





