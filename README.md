# Hackathon-Project-AI-Now-
## Project on Road Safety And Accident Intelligence Analysis And Visualization
### Project Overview
The Road Safety and Accident Intelligence Dashboard is a data driven solution designed to monitor, analyze, and visualize road traffic accidents and emergency response performance. The project integrates accident records, emergency response data, road network information, weather conditions, vehicle details, and safety intervention data into n interactive dashboard that supports evidence-based decision-making. 
The dashboard provides key performance indicators (KPI) such as the total number of accidents, fatalities, injuries, Emergency response time. It also enable users to analyze accidents by state, road type, years and month. 

### Problem Statementnn

 Road traffic accidents continue to have significant social and economic consequences in Nigeria, resulting in loss of life, injuries, property damage, traffic congestion, and increased emergency response costs. Road safety agencies collect accident reports, emergency response data, and infrastructure information from multiple sources. 

However, these datasets are rarely integrated into a unified analytical platform capable of identifying accident hotspots, evaluating contributing factors, or measuring the effectiveness of road safety interventions. 

Transport authorities require a comprehensive analytics solution to monitor accident trends, evaluate emergency response performance, identify high-risk road segments, and prioritize infrastructure improvements that enhance road safety. Participants are expected to develop a Power BI dashboard that supports evidence-based road safety planning and operational decision-making.

### Objectives
- Identify accident patter 
- High risk location
- Contributing factors.
- Response efficiency to improve road safety outcomes. Through the use of business intelligence tools such as Microsoft Power BI, the dashboard transforms - - -- complex datasets into meaningful insights that help government agencies, road safety authorities, emergency responders, and policymakers make decisions.

### Data Source
The Primary Source of Data used here is Data Accident Report.cvs and this an Open Source that can be Downloaded  from an OpeN Source Online such as Kaggle or any other Repository  

### Tools Used
- Microsoft Power BI
  1. For Cleaning Data
   2. Modelling the Tables
   3. Analysing
   4. Data Visualization
- GitHub for Portfolio Bulding

### Data Cleaning And Preparation
In the initial phase of data cleaning and preparation, i performed the following actions;
   1. Data Loading and Inspection
   2. Handling Missing Values
   3. Data Cleaning and Formating

### Exploratory Data Analysis
the EDA involve the exploring of the Data to answer some questions about the Data such as;
1. KPIs which are;
 - what is the Total Accident Occurrence in the Space of Three Years
 - Total Fatality
 -  Total Injured
 -  Total vehicles Involved
 -  Average Response Time
2. Accident Based Report
  - Total Accident by state
  - Pick of accident By Year and Month
  - Fatality By state
  - Fatality By Year and Month
3. Accident Contributing Factors
  - weather Conditions in Relation to accident Occurrences
  - Vehicle Types with accident Rate
  - Accident by Road Classification
  - Other Physical Factors Related to drivers such speeding distraction etc.
 4. Average Response Time
  - Average Response by Response Agencies
  - Average Response in Different Weather Conditions
  - And Road Types
 5. Safety Intervention Cost.

 ### Data Analysis
 ``` in Power BI =
Total Accident =
COUNTA('Accident Reports'[AccidentID])
```

```in power bi
Total Fatal Accident = CALCULATE(
     COUNTROWS('Accident Reports'),
         'Accident Reports'[Severity]="Fatal")
```
```in power bi
Average Response Time =
AVERAGE('Accident Reports'[Response Time Minutes])
```   
```in power bi
Total Cost =
SUM('Safety Interventions'[Cost])
``` 

 ```in power bi
Total Vehicles in accident =
COUNTA(Vehicles[Vehicle_ID])
```
    
       
    
