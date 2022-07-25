# PyBer Analysis Challenge

## Overview of the analysis
    
This project is a summary of two (2) reports: city data and ride data in order to analyze the Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver based on City Types: Rural. Suburban, and Urban.

We used merged dataframes in order to group and summarize the results, then used Matplotlib to create a visual chart that represents the statistical analysis of this challenge.

## Results
    
For this analysis, there are three (3) city types that we analyzed and we concluded based on the results shown in figure 1 that Urban cities has the highest number of Total Rides which is why there are a lot of drivers in those cities. Although, Urban cities has the lowest average fare per ride and driver, it has the highest total fares because there are a lot of rider in those cities.

On the other hand, Rural cities have the most expensive average fare per ride and driver but have the least total rides and drivers among the three city types.

**Figure 1: PyBer Summary Data**
![PyBer_Summary_Analysis](https://raw.githubusercontent.com/Mishabatoon/PyBer_Analysis/main/analysis/PyBer_fare_summary.png)

Let's now analyze the Total Fare by City Type as shown below (figure 2). We only analyze the data from January 01, 2019 until  April 28, 2019 and resampled the time series on a weekly basis. At first glance, we can conclude that Urban cities have the highest total fares, and rural cities have the lowest total fares.

**Figure 2: Total Fare By City Type**
![PyBer_Analysis_Plot](https://raw.githubusercontent.com/Mishabatoon/PyBer_Analysis/main/analysis/Total%20Fare%20by%20City%20Type.png)


In reference to figure 3, Rural has the highest total fares during the week of April 7th which has a total of $501.24. Suburban's highest total fares was during the week Feb 24th with a total of $1,412.74. While, Urban's highest total fares was during the week of March 10th with a total of $2,470.93.



**Figure 3: Total Fares Table**

![Total Fare Table](https://raw.githubusercontent.com/Mishabatoon/PyBer_Analysis/main/analysis/Total%20Fare%20Table.png)


# Summary
Urban rides have the lowest Average Fare per Driver and lowest Average Fare per Ride but has more drivers than total rides. However, Rural and Suburban rides have the higher Average Fare per Driver and higher Averager Fare per Ride but have more rides than the number of drivers. It is likely that drivers think that there are more rides available in the urban area, which cause a driver surplus. Alternatively, it is likely that drivers think there are less rides in rural and suburban areas causing driver scarcity.

* An ideal situation is to balance the ratio of `Total Rides/Total Drivers` closest to 1 . 

* A possible solution would be to incetivize during periods of surplus and scarcity so drivers are willing to expand their driving scope so that the number of drivers match the number of requested rides more equally.

* An algorithm/app can be developed to dynamically optimize the number of drivers, based on the real time data  organized in this manner
