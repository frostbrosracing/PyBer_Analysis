# PyBer Analysis Based on City Type

## Project Overview of the PyBer Analysis
#### This project was completed to provide insights to the CEO of PyBer based on an analysis of ride data from the first four months of 2019.
The analysis was conducted by grouping cities according to what type of city they were.  These types were: ***urban***, ***suburban***, and ***rural***.  By classifying cities in this way, we're able to begin to see trends based on summarized data collected based on a number of factors.  

  1.  Total rides summarized by city type
  2.  Total drivers summarized by city type
  3.  Total fares summarized by city type
  4.  Average fare per ride summarized by city type
  5.  Average fare per driver summarized by city type
 
 In addition to these summarized values, a graphical visualization of the total fare revenue broken down by city type and grouped by week for the period being analyzed was rendered.
 
#### Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.7.9, Jupyter Notebook 6.1.4, Pandas 1.1.3, Numpy 1.17.0, Matplotlib 3.3.2
 
## PyBer Analysis Results
The results show that between the ***urban*** and ***rural*** city types, there's a great disparity in the summarized values for each of the figures being calculated.  The ***suburban*** city type falls reasonably well placed in the outcome of the analysis, and therefore the scope of this analysis focuses on closing the revenue gap between the highest and lowest areas.  The image below shows the totals and averages for all calculated summaries.

![PyBer_summary_dataframe.PNG](https://github.com/frostbrosracing/PyBer_Analysis/blob/main/analysis/PyBer_summary_dataframe.PNG)

### 1. Total Rides by City Type
Because of the dense population of cites categorized as ***urban***, total ride volume is inherently greater in these locations than in ***suburban*** or ***rural*** areas.  As shown in the summary dataframe below, the total number of rides in ***urban*** city types is **13 times greater** than the total number of rides in ***rural*** city types. 
### 2. Total Drivers by City Type
Again, because of population density being greater in ***urban*** areas, the total number of drivers is significantly greater than in ***rural*** city types.  Here we see an increase of **30 times** the number of drivers.  
### 3. Total Fares by City Type
The total revenue generated by fares is directly related to the total number of rides.  Here we see almost **10 times** the revenue generated in ***urban*** versus ***rural*** city types.  
### 4. Average Fare per Ride by City Type
The average fare per ride is much more closely related than any of the other key metrics obtained in this analysis.  
### 5. Average Fare per Driver by City Type
Some interesting observations can be made within this summary.  Here we see that even though there is such a significantly smaller revenue total, because there are so few drivers in ***rural*** city types, the average fare per driver is much greater than in ***urban*** city types.  It's here that the following recommendations begin to take shape.

## PyBer Analysis Summary
Based on the analysis it is clear that there's an underserved community in rural city neighborhoods by drivers.  As shown in the chart below, ridership is fairly consistent for the period covered.  This consistency is a key component to targeting areas for improvement to the company's bottom line.  

![Pyber_fare_summary.png](https://github.com/frostbrosracing/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

In order to balance the distribution of driver coverage to different ride areas the following recommendations should be considered with the goal of increasing overall company revenue:

1.	A slight decrease in the overall cost to consumers using the PyBer service in ***rural*** city types will likely increase demand in those areas.  
2.	Based on the increased demand of rides generated from the adjusted prices in rural areas, it will be necessary to increase the driver availability in those areas.  By offering incentives to drivers who provide that coverage, the overall number of drivers will slightly decrease from the urban areas as they begin to provide service in the outlying areas.
3.	This decrease in total supply of drivers in urban areas will cause an increase in the demand and therefore justify an increase in the total fares, the average fare per driver and consequently help close the gap in total revenue between ***rural*** and ***urban*** city types.

By putting these recommendations in place, PyBer can not only increase overall revenue, but also invest in long term rider loyalty by gaining exposure to a new customer base previously unserved by the company.
