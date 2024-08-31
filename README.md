# COVID-19 Impact on Airport Traffic

### Project Overview

This dataset shows traffic to and from the Airport as a Percentage of the Traffic volume during 
the baseline period. The baseline period used for computing this metric is from 1st Feb to 15th 
March 2020


![image](https://github.com/user-attachments/assets/cbbab8f8-3b5e-4927-84b0-57d1eb9e1f2a)


### Data Sources

The primary dataset used for this analysis is the "Covid_impact_on_airport_traffic.csv" file from **QUANTUM ANALYTICS** contained detailed information about the percentage baseline, country and state 

### Tools 
- Power Query - Data Cleaning
- Power BI- Data Analysis
- Power BI - Create Report

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following task:

1. Loading data on Power query
2. Inspection and aligning 
3. Data cleaning and formating
4. Loading data for Analyzing
5. Create new measures 

### Exploratory Data Analysis

EDA involved exploring the COVID-19 Impact on Airport Traffic to answer key question such as:

- What is the percentage baseline by country
- What is the percentage baseline by month
- What is the percentage baseline by State
- What is the percentage baseline by Airport
- What is the percentage baseline by ISO_3166_2
- How many county and in how many city
- How many Airport 


### Data Analysis

Include some interesting formula worked with

```
 POWER BI
- count airportname = DISTINCTCOUNT(covid_impact_on_airport_traffic[AirportName])
- count country = DISTINCTCOUNT(covid_impact_on_airport_traffic[Country])
- count city = DISTINCTCOUNT(covid_impact_on_airport_traffic[City])

```

### Results/Findings

The analysis results are summarized as follow:
1. Despite the COVID-19 Quebec still have more traffic than other state airport in consideration 
2. Airport traffic reduce drastically in December
3. Airports in the United State combine together have the highest traffic during COVID
4. Airport in Chile have the lowest airport traffic among the 4 state in consideration
 

### Recommendation

Based on the analysis, we recommend the following actions:
- During major outbreak, airports should put measures in place to avoid the diseases moved to another Country because that will not allow the diseases to spread as we have in COVID period 



### References

This data is publicly available from Geotab (geotab.com).
