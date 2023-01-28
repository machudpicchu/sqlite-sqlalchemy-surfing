# Surf's Up--Module 9 Challenge
## Overview of the Statistical Analysis:
The narrative of this module follows a person who is wanting to open a small business in Hawaii.  He has created a report for investors to show the weather conditions in order to assure them of the favorable weather conditions around the location of the small business.  The report requested was for the weather data, requesting specifically the temperatures for the months of June and December.  

These numbers were found by using Python, Pandas, and SQLAlchemy to filter the temperatures for the months of June and December in the hawaii.sqlite database. A dataframe was then created from the database in order to gain summary statistics.

This information will be used in a report to potential investors to influence their decision to support the small business.

## Results
When comparing June and December, the following differencess were noticed from comparing the following charts.  
![June Temperature Chart](https://github.com/machudpicchu/surfs_up/blob/main/June%20Temps.png)
![December Temperature Chart](https://github.com/machudpicchu/surfs_up/blob/main/Dec%20Temps.png)

### Difference 1:
The December temperatures have a lower minimum, measuring 56 degrees, compared to a minimum temperature of 64 degrees in June. 

### Difference 2:
The maximum temperatures are more similar, but December is slightly cooler, having recorded a maximum temperature of 83 degrees in December to 85 degrees in June.

### Difference 3:  
The average temperature in June is 3.9 degrees warmer than December as June's average temperature is 74.9 degrees and December's average temperature is 71.0 degrees.

## Summary:
Given this information, June and December are very similar in temperatures based on this data.  Their average temperatures are only 3.9 apart, and the standard deviations of their temperatures indicate that most of the time, the temperatures are within four degrees higher or lower from the average.  

When considering what additional information for investors could be gleaned from the data we have, the following additional queries are recommended.
### Query 1
During which months are the highest temperature and least rainfall?  This information could be determined by gathering statistical data on rainfall across the different months in the dates we have.  This information could help determine which specific months of the year are most favorable for visitors to visit.

### Query 2
When looking at the minimum temperatures in December and June, are those strictly the results of cooler temperatures in the mornings, or are there days when the weather is cooler all day?  This could be learned by filtering the temperatures by the time of day in which the data is recorded.  This could help to determine customer satisfaction and how to best cater to the surfing habits of visitors.
