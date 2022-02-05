# PyBer Analysis

## Overview of the analysis

Pyber is a ride-sharing company with over $2B in sales.  The purpose of this analysis is to develop a summary of the ride-share data by city type for the period of January to May 2019.  In addition, a visualization of the total weekly fares for each type will be developed.  Leveraging both the summary data and visualizations, this report will show the differences by city type in PyBer ride-share data and develop recommendations.


## Results

### Summary Data Analysis
Before analyzing the summary data, one observation about the data itself which is worth pointing out is that the number of cities by type in the data set is different.    **_Figure 1: City Count by Type_** shows there are 66 urban cities, 36 suburban and 18 rural cities in the data set.  

![City Count by Type](/resources/city_count.png)

In **_Figure 2: City Type Summary_** we can make the following observations:

- The average fare per ride is higher in rural cities - likely due to longer distances and duration.  There could be other factors for the higher fare average but the case does not reveal additional information about whether there are mulitple service types.
- Rural drivers make more than Urban drivers because there are less drivers as a percentage of total rides.  The total drivers divided by the number of rides is 62.4% for rural cities versus 148% for Urban city types.  There is simply more competition amongst drivers in the urban cities.
- The suburban averages fall in the middle of the two bookends that being rural and urban.

Comparisons or conclusions about the total number of rides, drivers and total fares cannot be made from this summary table because the total number of cities by city type differs.  The city type with the highest number of cities will naturally result higher values.

**_Figure 2: City Type Summary_**

![City Type Summary](/resources/City_Type_Summary_df.png)

### Weekly Fare Analysis

**_Figure 3: Weekly Fares City Type_**

![City Type Summary](/analysis/Total_Fare_by_city_Type.png)

The line chart simply shows the total revenue per week by city type.  Revenue is highest in the urban city total however it has the most cities which is 66 as compared with suburban at 36 cities, and just 18 for rural.

## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

Before summarizing the results and drawing conclusions is important to list what we don't know about the data which might skew the observations.  For example, fares for ride-sharing services are based on distance and duration, this is likely common for each city type, but it is entirely possible that the prices applied to this algorythm might be different by city type.  This analysis assumed it was the same price in all city types.  In addition, ride-share services often provide a selection of service types like green, luxury, or economic which would have their own price points and once again it is unclear if this type of variety existed in the data we assume it is not a factor.

There are other limitations in this data set which included could proved insightful.  First, the data set is for 5 months of the year which may or may not be representative of all periods.  Furthermore, additional city characteristics could provide more insights.  For example, if you have two cities which are relatively the same in population size you might expect the number of ride and fare averages however things like household average incomes, the number of sporting or entertainment venues, and strength of local economy will likely impact consumer behaviour not to mention the number of competitors in the city.   Other considerations are the types of roads in the city such as paved vs dirt or toll highways vs free which can have an impact on the average fare prices because the duration variable in the pricing algorythm would increase or decrease.

### Recommendations

There are no recommendations I would make to the CEO until I understand from the CEO what their objective is or rather what problem do they want to solve.  

For example, if the CEO were to indicate that driver turnover in Urban cities is high due to the average fare per driver being low there are two levers which could change this outcome.  The numerator, fares, could be adjusted to charge more in urban cities and/or the denominator, number of drivers, could be reduced by making the qualifications to become a driver for PyBer more strigent.  When making these kinds of choices additional analysis may be required.  If for example we choose to increase the price, the impact my be positive for the drivers at first but in short order their earnings may begin to fall again due to less rides as competitors with a lower prices steal market share.  Before we finalize the decision to increase price analyzing price elasticity becomes very important along with a SWAT analysis the competitors.

Alternatively, if we leave price alone and cull the driver pool.  Once again, existing drivers would benefit from more rides however over time consumers may have to wait longer for a driver to show up and this could lead to customer abandonment if competitors are doing a better job on this KPI.

Given it is a gig economy the CEO may not be as concerned about the average fare per driver.  They may be more focused on service availability which when high should result in more rides and more revenue (maybe).  The answers and recommendations require a multi-variant analysis of many data points.  The solutions and recommendations one makes are dependent on which KPI's you want to change and the correlation between KPI's so that one goal does not negatively impact another.  

In order to better understand the opportunities to grow the business in any of the three city types I would recommend the CEO gather more information in the following areas:
- Competitor performance, 
- Customer sentiment analysis,
- Website analytics to understand usability and abandonment factors, and
- Accessiblity to the internet and on the website itself.
