# PyBer_Analysis

An analysis of disparities in ride-sharing data among city types.

# Overview
A data analyst at PyBer, a ride-sharing app company valued at $2.3 billion, was given the following tasks:
- create a ride-sharing summary DataFrame by city type 
- create a multiple-line graph showing the total weekly fares for each city type
- prepare a summary report of the data differences by city type and how those differences can be used by decision-makers at PyBer

## Resources
Data Source: city_data.csv, ride_data.csv, PyBer_ride_data.csv
Software: Conda 4.10.3, Python 3.7.6, Jupyter Notebook 6.3.0, Pandas, and Matplotlib

# Results
- The following Ride-Sharing Summary DataFrame by City Type was created using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns. The total number of rides, total number of drivers, and total fares for each city type was generated. The average fare per ride and average fare per driver for each city type was also calculated. 
![PyBer_sum_df.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/Resources/PyBer_sum_df.png)

- The following Multiple-line Graph of Total Weekly Fares for Each City Type was created using the Pandas pivot() and andresample() functions.
![PyBer_fare_summary.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png)

Based on the above results, there are significant differences in ride-sharing data among the different city types:
- The total number of rides by city type was 68.4% (Urban), 6.3% (Suburban), and 5.3% (Rural).
- The total drivers by city type was 80.9% (Urban), 16.5% (Suburban), and 2.6% (Rural)
- The total fares by city type was 62.7% (Urban), 30.5% (Suburban), and 6.8% (Rural).

Whereas, the opposite can be said for the average fares per ride and driver. The higher fares in rural and suburban cities may be contributed to the distance traveled and fuel costs.

# Summary
Based on the results, three business recommendations can be made for PyBer as follows:
1. Additional research should be conducted to identified more factors that contribute to the higher fares in rural cities compared to suburban and urban. Drivers in rural cities are earning more than drivers in urban cities. However; the additional time, vehicle wear, and fuel may be the difference. 
2. A stronger marketing campaign should be put in place at the end of February as there is a signifant drop in fares right after Valentine's Day in all city types.
3. PyBer might consider eliminating the rural service as it does not appear too profitable. If it does not eliminate service to rural cities, it might consider offering more specialized services with higher fare rates.

Other Analysis Graphs generated from the ride-sharing data that supports the summary and line chart above:
![Fig1.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig1.png)
![Fig2.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig2.png)
![Fig3.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig3.png)
![Fig4.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig4.png)
![Fig5.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig5.png)
![Fig6.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig6.png)
![Fig7.png](https://github.com/KimberlyCrawford/PyBer_Analysis/blob/main/analysis/Fig7.png)
