# PyBer_Analysis

## Overview

We were tasked with analyzing ride share data for cities across the US. Our goal was to understand driver and fare impact for different types of cities (rural, urban and suburban), and make recommendations for improvements to the ride share service. To understand the type of data we are working with to be able to make the appropriate recommendations, we will be creating multiple Data Frames and separating each city type based on the total number of drivers, total fares, average fare price per rider, and average fare per driver. By doing this, we hope to gain more insight into why certain cities types have higher fares prices and what can be done to reduce fares or increase driver support.

### Resources

#### Data Sources
city_data.csv
Pyber_ride_data.csv
ride_data.csv

#### Software
Python 3.9
Jupyter Notebooks 6.1.4
Anaconda 3.8.5

#### Code Techniques
Pandas
Numpy
Matplotlib

## Results

After creating our data frame, we got the following DataFrame:

https://github.com/roderickspells/PyBer_Analysis/blob/main/analysis/Pyber_Summary_DataFrame.png

As seen above, we determined the total number or rides, drivers, total fares, average fare per rode and average fare per driver in three categories of cities, Rural, Suburban, and Rural.

We can see that Urban cities have the highest total or rides, drivers, and fares. Rural cities have the least amount of total rides, drivers, and fares.

With this output we can reasonably conclude that the more rides in a city, the more drivers there are. The more drivers in a given market, will bring the average fare per ride down, but the overall amount of rides with result in a higher total of fares. The more rides, the more opportunities there are to collect a higher total of fares.

Rural cities have the least amount of drivers and rides which will yield a higher fare per ride as well as a higher average fare for drivers. A reasonable conclusion would be that urban and suburban cities have an advantage over rural cities due to their access to more people due to higher population sizes. Average fares per ride and drivers will be higher in a city where trips are more likely to be longer in time and in distance in more open areas in rural cities compared to shorter trips in urban city landscapes.

We also wanted to see if the time of year impacted the number or drivers or fares so we created a charted to gain insight. The below chart shows total fares by city types from January to April 2019.

https://github.com/roderickspells/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png




## Summary

Overall we can conclude that higher populated cities have more access to drivers and can provide more rides. Rural cities will have less drivers and thus less rides because of the population is going to be much lower.
If I could offer and recommendations it would be to:

Offer an incentive program to attract more drivers in the rural markets . If you are able to bring more drivers to the area, it could bring down fare costs and be more attractive to potential riders.
