# PyBer_Analysis

An analysis of how to address disparities in ride-sharing data among city types.

# Overview
A data analyst at PyBer, a ride-sharing app company valued at $2.3 billion, was given the following tasks:
- create a ride-sharing summary DataFrame by city type 
- create a multiple-line graph showing the total weekly fares for each city type
- prepare a summary report of the data differences by city type and how those differences can be used by decision-makers at PyBer

## Resources
Data Source: city_data.csv, ride_data.csv, PyBer_ride_data.csv
Software: Conda 4.10.3, Python 3.7.6, Jupyter Notebook 6.3.0, Pandas, and Matplotlib

# Results
- Ride-Sharing Summary DataFrame by City Type: Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, get the total number of rides, total number of drivers, and the total fares for each city type. Then, calculate the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, then format the columns.
![PyBer_Summary_DataFrame](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/Resources/PyBer_Summary_DataFrame)

- Multiple-line Graph of Total Weekly Fares for Each City Type: Using your Pandas skills and two new functions, pivot() andresample(), create a multiple-line graph that shows the total fares for each week by city type.
![PyBer_fare_summary.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png)

Other Analysis Graphs:
![Fig1.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig1.png)
![Fig2.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig2.png)
![Fig3.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig3.png)
![Fig4.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig4.png)
![Fig5.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig5.png)
![Fig6.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig6.png)
![Fig7.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig7.png)

Based on the above results, the differences in ride-sharing data among the different city types includes:
- Urban cities have the highest ridership demand while rural cities have the least.
- Urban cities have 4x+ more drivers than suburban cities.
- Suburban cities have 6x + drivers than rural with almost 4.5x the revenue.
- Rural cities have the highest average fare per ride and driver.
- The summary data shows a relationship in which fare revenue is higher by city type when there is a larger ratio of drivers to rides.

There is a larger use of PyBer ridesharing in urban cities.
There are more drivers in urban cities than rural cities.
As a result, the majority of PyBer's revenue occurs in urban cities.
On the other hand, the costs for using PyBer is greater among riders in rural cities than urban cities. This could discourage potential riders from using PyBer given the high average fare per ride.
Drivers in rural cities are earning more than drivers in urban cities. This could discourage discourage potential drivers from working with PyBer given the low average fare per driver.
There is an another opportunity for further analysis to determine other factors that are contributing to the high ride costs in rural cities and low driver fares in urban cities. Perhaps, travel distance is a key factor.
Overall, PyBer ridersharing services significantly differs in rural, suruban, and urban cities given the number of rides, drivers, and fares. Data supports that there is higher usage of PyBer ridesharing services in urban cities.

# Summary
Based on the results, three business recommendations can be made for PyBer as follows:
1.
2.
3.

