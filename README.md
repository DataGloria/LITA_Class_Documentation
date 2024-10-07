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
This Project aims to  analyze an hypothetical Company called International Breweries. We use SQL Queries to generate insights that will be important for decision making in the organization
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
  This involved Exploring of Data to answer strategic questions;
  Which brand generated the most profit?
  which region generates the most profits?
  what is the total profit generated by each coutry in a specific year? etc

  

   ### Data Analysis
 This is where we include some basic lines of code or queries or even some of the DAX Expression used during the analysis

 ```SQL

SELECT Countries,
	CASE
	WHEN Countries IN ('Nigeria', 'Ghana') THEN 'Anglophone'
	ELSE 'Francophone'
	END AS Country_groups,
SUM(Profit) AS Total_Profit
FROM[dbo].[International_Breweries]
WHERE Years between 2017 and 2019
GROUP BY Countries
ORDER BY 3 DESC
```


 ### Data Visualization

