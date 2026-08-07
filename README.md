# Hackathon-Project-AI-Now-

<img width="1076" height="566" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/11c11629-a905-4e47-81a9-7eddeaeb8641" />


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
<img width="103" height="85" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/de829d84-46bf-4086-b058-c15f86778148" />

```in power bi
Total Fatal Accident = CALCULATE(
     COUNTROWS('Accident Reports'),
         'Accident Reports'[Severity]="Fatal")
```
<img width="113" height="81" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/ab299e90-a5e5-4eee-b71c-05582257326e" />

```in power bi
Total Injured =
SUM('Accident Reports'[Persons Injured])
```
<img width="188" height="140" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/b8df9350-452a-40b4-b106-56167c3cad21" />



```in power bi
Average Response Time =
AVERAGE('Accident Reports'[Response Time Minutes])
```   
<img width="158" height="77" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/8ffbc24b-0968-43a8-a32a-73b6aa58e4e9" />


```in power bi
Total Cost =
SUM('Safety Interventions'[Cost])
```
<img width="126" height="78" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/419ad310-e2fc-4ed4-baf7-afd9fea1a7c0" />


### Visualization
---
#### Accident By Accident Type
       
  <img width="1260" height="616" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/632d4c48-4eca-4aa6-a5c6-0b49e7551386" />

#### Accident By Time of Day
 <img width="1257" height="574" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/8ce93396-2f98-4570-87a8-8f02d552a9a5" />

#### Accident By State

<img width="1234" height="590" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/2a02e3db-ceca-4d6d-ab3f-a0421c6877ff" />

#### Accident By Year

<img width="1269" height="604" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/afaa7a37-6294-4b3e-a662-fcc218233ff1" />

#### Accident By Month
<img width="1283" height="609" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/9e035e53-3ecd-4d93-afb4-44b1b319a496" />


#### Fatality By State

<img width="1234" height="617" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/7e40e984-c70c-4d45-9406-6ca722132fdf" />

 #### Fatality By Month
 <img width="1261" height="557" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/ed80b9ad-4c43-4f86-bb72-4dab4cb779ec" />

#### Fatality By Year
<img width="1264" height="594" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/3aefbd28-aa3a-4191-adb9-c95e2831ca6b" />

#### Injured By Severity
<img width="1265" height="609" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/c0ec2687-372d-4b7d-8c27-858d5693dfb2" />

#### Injured By Accident Type
<img width="1262" height="602" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/f88db3d7-5401-4cf3-8e77-21ea13dc83a5" />

### Accident Related Factors
---
#### Accident By Weather Conditions
<img width="1274" height="617" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/a1ee1733-cd0d-4b37-bd76-0c4b9d4acff6" />

#### Accident By Vehicle Type
<img width="1257" height="609" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/cf4fd022-cb3a-4ff0-8ea1-36a616894475" />

#### Accident By Road Classfication
<img width="1260" height="603" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/2ee14246-2ff6-4ca7-bcfd-858f71eff985" />

#### Accident By Driver's Factors
<img width="605" height="1262" alt="Screenshot (59)" src="https://github.com/user-attachments/assets/bfc721fe-98b5-430e-a92e-4dde41217f45" />

#### Accident By Road Surface
<img width="1280" height="609" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/1fd7caef-5872-4d42-9b28-e1a4351f8fdb" />

#### Accident By Road Type

<img width="1274" height="621" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/49064763-15b0-418e-8d5c-71ccad33925b" />
### Tables Relating Showing Patterns of Accident In Relation to Vehicle Types and Weather Conditions 

<img width="1250" height="593" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/c108f167-b832-4c5e-9610-18b14fedd1dc" />

Out of 9968 Vehicles Tracked in the Space of 3 Years, 1500 of them were involved in road accident. The breakdown of the vehicle type is shown above using unique count.


<img width="510" height="377" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/65285a2a-13be-4d93-b197-b2b7daf5e28e" />


#### A Pattern Analysis

Analysis of this part of the accident data indicates that 
cars recorded the highest number of road traffic accidents during clear weather conditions compared to all other weather categories. this trend suggests that favorable weather does not necessarily reduce accident occurrence. instead, the higher accident frequency during clear conditions is likely influenced by increased traffic volume, greater vehicle usage, and a tendency for drivers to travel at higher speeds or become less cautious when road conditions appear safe. This findings highlight the importance of maintaining safe driving practices regardless of weather conditions . This is a pattern that cut aross the 36 States of Nigeria Including FCT.

### Recommendations

Based on the analysis of road safety and accident intelligence data, the following recommendations are proposed to improve road safety,  reduce traffic accidents, and enhance  emergency response effectiveness

- Prioritize High Risk Locations: Road safety authorities should identify accident hotspots and prioritize them for infrastructure improvements such as better road markings, traffic signals, pedestrian crossing and street lighting
- Emergency response teams should be strategically deployed based on accident frequency and response time analysis
- Increase traffic law enforcement : Traffic enforcement agencies should intensify monitoring of speed limits, dangerous driving behaviors,  overloading, and other traffic violations through regular patrols and cameras.


