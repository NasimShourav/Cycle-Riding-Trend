# Cycle-Riding-Trend project Summary


Following the framework of the data analysis process: **Ask, Prepare, Process, Analyze, Share, and Act** , this case-study was designed to address the key business question which is **Maximize the number of annual memberships by converting casual riders to annual members**. 

**1. Ask**

In order to find the answers, the project manager assigned couple of task to different individuals.

a. How do annual members and casual riders use Cyclistic bikes differently?
b. Why would casual riders buy Cyclistic annual memberships?
c. How can Cyclistic use digital media to influence casual riders to become members?

As a junior analyst, I was assigned to answer the first question.

**2. Prepare**

I am considering four months data (from Jan 2022 to Apr 2022).
Content: Dataset contains 15 fields which contain data such as ride id, rideable type, dates, geographic data etc. Total data records were 864K.

The raw data set can be found in https://divvy-tripdata.s3.amazonaws.com/index.html 

**3. Process**

I have cleaned and processed the dataset using excel. Steps taken were: 

1. Check the ride id. Omit the records where ride id is greater or less than 16.
2. Create new column, ride duration, by subtracting ending time from starting time.
3. Replace the missing variables with NULL since it constituted only <1% of the records.

The consolidated data can be found [here](https://docs.google.com/spreadsheets/d/1nf2DCYvSCXnPLckF5q7Is0cZYwhzTcTh/edit?usp=sharing&ouid=117562808745634962721&rtpof=true&sd=true)

**4. Analyze**

With SQL's DML, DCL, DDL, and functions generates various insights form the datasets. 

**5. Share**

The aggregated data then has been [visualized](https://public.tableau.com/app/profile/nasim.al.goni/viz/BicycleRiding/Dashboard1) with the help of Tableau Public.

**6. Act**

Based on the analysis, my recommnedation will be: 

1. Its better to online advertise or run promotional campaign for casual riders from 5pm to 12 am
2. Streeter Dr & Grand Ave will be an excellent choice to run static marketing campaign 
