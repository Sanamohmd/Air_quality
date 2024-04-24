# Air_quality and Asthma analysis

Analysis of Air Quality and Asthma

Table of Contents:


•	Tableau Dashboard
•	Motivation
•	Data Questions
•	Data Cleaning
•	Challenges
•	Technologies Used
•	Sources
•	Conclusion


Tableau Dashboard:


Motivation:

As a dentist with experience in patient care and health management, I’ve always been fascinated by the intricate connections between environmental factors and human health. Having a personal history with asthma I'm eager to delve deeper into understanding how air quality impacts respiratory health, particularly in individuals with asthma.


Data Questions:

1. Find correlation between air quality and prevalence of asthma in adults and children.

2. Analyze Asthma mortality rate by states.

3. Find out how many days each major city in the US has good air quality.

4. Analyze air quality trends in Tennessee.


Data Cleaning:

The datasets for asthma had data from 2017 – 2021 on the CDC website, so I also picked datasets from 2017 to 2021 from the EPA for air quality data. I created multiple dataframes for the years 2017 - 2021.



Challenges:

All the datasets were separate, I had to create a dataframe for all 50 states and then merge them with Asthma statistics to compare the two. 
Some data that was given were incomplete or incorrectly recorded and have to change a few datatypes to merge them.


Technologies Used:

Python/Pandas – for exploration, normalizing and aggregation of dataset.
Tableau – for dashboards
PowerPoint for introducing the project 



Sources: 
1.	https://www.cdc.gov/asthma/most_recent_data_states.htm
2.	https://www.cdc.gov/asthma/brfss/2021/child/tableC1.html
3.	https://www.epa.gov/outdoor-air-quality-data/air-quality-index-report
4.	https://www.epa.gov/air-trends/air-quality-cities-and-counties
5.	https://healthdata.tn.gov/Environmental-Health/Nashville-Air-Quality/ryih-rhnf/about_data



Conclusion:

My analysis shows that there is no correlation between bad air quality and asthma and there may be a slight tendency for higher asthma percentages to coincide with higher maximum AQI values. The relationship is complex and other variables such as individual susceptibility, geographical factors and socio-economic status may also influence prevalence of asthma. Therefore, while improving air quality is undoubtedly beneficial for public health, addressing asthma comprehensively requires a multi-faceted approach. 



