# Analyzing Police Shootings in the U.S. since 2015

## Background and Problem Statement
In recent years, particularly since the fatal shooting of Michael Brown in Ferguson, Missouri in 2014, police brutality has become an alarming issue in the United States. Increased media coverage due to high-profile cases has increased awareness across the globe on lethal police force, yet research on those fatalities are not widely known. What are the statistics of being fatally shot by the police given social demographics? We will explore this topic with the use of data from the Washington Post. 

### Data Used 

* [`fatal-police-shootings-data.csv`]('./fatal-police-shootings-data.csv'): The Washington Post's csv contains records of every fatal shooting in the United States by a police officer in the line of duty since Jan. 1, 2015.



### **Data Dictionary**

|Feature|Type|Dataset|Description|
|---|---|---|---|
|id|int|police|Unique identifer for each victim| 
|name|object|police|Name of the victim| 
|date|object|police|Date of the fatal shooting| 
|manner of death|object|police|Shot or Shot and tasered| 
|armed|object|police|Indicates if the victim was armed| 
|age|float|police|Age of the victim| 
|gender|object|police|Gender of the victim| 
|race|object|police|Race of the victim| 
|city|object|police|City of the fatal shooting| 
|state|object|police|State of the fatal shooting| 
|signs_of_mental_illness|bool|police|Indicates if the victim had signs of mental illness| 
|threat_level|object|police|The police officer's objective measure of threat from the victim| 
|flee|object|police|Was the victim attempting to leave the scene?| 
|body_camera|bool|police|Did the police officer have body camera turned on?| 
|longitude|float|police|Longitude Coordinates| 
|latitude|float|police|Latitude Coordinates| 
|is_geocoding_exact|bool|police|Accuracy of the coordinates| 


## Executive Summary
* Background and Problem Statement
* Data Import & Cleaning
* Exploratory Data Analysis
* Data Vizualization
* Conclusions/Recommendations


## Findings
Since the year 2015, there has been over 6,000 fatal police shootings. We have analyzed over these fatal police shootings within the United States from January 2015 until Feburary 2021. The data shows that the rate of fatal police shootings year to year has been steady since 2016. Most of these victims have been indentified as males. The age of most victims varies, there has been some outliers at over 80 years old, but the average age is 36. This is alarming that most victims are very young, there has also been two victims who were only 6 years old. These two victims were not armed of course, as they are just kids. Surprisingly, most of the victims were 'White', when most media coverage is about blacks and hispanics. This data needs to be further explored with the cesus population to determine the actual percentage compared to the composition of race within the United States. The state of California has accounted for over 15% of all fatal shootings in the United States. Approximately 8% of the victims were unarmed. Over 50% of all victims were armed with a gun, which is another alarming statistic. This data needs to be further explored to examine if the victims had a legal right to carry. 
