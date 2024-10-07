# LITA_Class_Documentation
Documentation of my Projects while learning Data Analysis

### Project Title: International Breweries Analysis

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)
### Project Overview
---
This Project aims to  analyze an hypothetical Company called LITA plc. it involves the creation and population of the employee and payment table whuch contaims Employee information and payent details.

### Data Sources
 The primary source of Data used here is a csv file of this company as provided to us

### Tools Used

- Microsoft Excel for Data Cleaning and Analysis [Download Here](https://www.Microsoft.com)
- SQL- Strutured Query Language for Data Query
- PowerBi for Visualizaion

### Data Cleaning and Preparations
  in the intitial Phase, we performed the following actions;
  - Data Loading and Inspection
  - Handling missing Variables
  - Data Cleaning and Formatting
 
### Exploratory Data Analysis
  This involved Exploring of Data to answer basic questions;

  

   ### Data Analysis
 This is where we include some basic lines of code or queries or even some of the DAX Expression used during the analysis

 ```SQL

SELECT Staffid, firstname, gender, state_of_origin, Age,
CASE
	WHEN Age>=60 THEN 'Senior Executive'
	WHEN Age BETWEEN 40 AND 59 THEN 'Senior Manager'
	WHEN Age BETWEEN 30 AND 39 THEN 'Manager'
	WHEN Age <=29 THEN 'Assistant Manager'
	ELSE 'Unknown'
END AS Age_Group
FROM Employee
```


 ### Data Visualization


 ```SQL
