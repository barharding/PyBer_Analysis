# PyBer Analysis

## Overview of the analysis

Pyber is a ride-sharing company with over $2B in sales.  The purpose of this analysis is to develop a summary of the ride-share data by city type for the period of January to May 2019.  In addition, a visualization of the total weekly fares for each type will be developed.  Leveraging both the summary data and visualizations this report will show the differences by city type in PyBer ride-share data.  


## Results

In **_Figure 1: City Type Summary_** we can make the following observations:

- The average fare per ride is higher in Rural cities - likely due to longer distances and duration
- Rural drivers make more than Urban drivers because there are less drivers as a percentage of total rides.  For example, total drivers divided by # of rides is 62.4% for rural versus 148% for Urban city types.  There is simply more competition amongst drivers in the urban cities.  

Comparisions about the differences in the total number of drivers, total drivers and total fares cannot be made from this summary table because the total # of cities by city type differs.  This was verified by adding the code shown in **_Figure 2: City Count by Type_**.

![City Count by Type](/resources/city_count.png)



Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

**_Figure 1: City Type Summary_**

![City Type Summary](/resources/City_Type_Summary_df.png)

![City Type Summary](/analysis/Total_Fare_by_city_Type.png)



## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

Before summarizing the results and drawing conclusions about the results it is important to list what we don't know about the data which might skew the observations.  For example, fares for ride-sharing services are based on distance and duration this is likely common for each city type but it is entirely possible that the prices applied to this algorythm are different by city type.  This analysis will assume it is the same price.  In addition, ride-share services often provide a selection of service types like the options to select a Green trip, a luxury trip, economic trip etc... The prices would vary for each of these selections.  Again the analysis will assume it is the same price and that Pyber offers one service type in each city.

There are other limitations for this analysis which could prove insightful if the data included more data points.  First, the data set is for 5 months of the year which may or may not be representative of all periods.  Additional city characteristics more than just the type could provide more insights.  For example, if you have two rural cities which are relatively the same in population size you might expect the number of rides would be relatively the same.  That said, things like household average incomes, the number of sporting or entertainment venues, and strength of local economy and if this data were included it might show that these things are correlated to the number of rides.  Other considerations are the types of roads in the city such as paved vs dirt or toll highways vs free which can have an impact on the average fare prices because the duration variable in the pricing algorythm would increase or decrease.
