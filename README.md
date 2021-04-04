# PyBer Analysis

## Purpose of Analysis

The CEO of Pyber has tasked me with analyzing the company's ride-share data using python's pandas, numpy, and matplotlib libraries. He wants me to provide insight on the differences between the three city types: urban, suburban, and rural. The main areas that I look into through this project are, a general overview, rides, drivers, and fares in all three city types.

## Results


There are 4 different areas of analysis needed to complete this project. These are:

1. Overview of City Types
2. Rides per City Type
3. Drivers per City Type
4. Fares per City Type

### Overview of City Types

The overview of the city types consists of a bubble chart highlighting the comparison of rides, drivers, and fares. Drivers are represented by the size of the bubbles, fares by the y axis, and rides by the x axis.

![overview_of_data](https://github.com/Wall-E28/pyBer_analysis/blob/master/analysis/Fig1.png)

### Rides per City Type

Rides per city type is broken up into two different categories: rides per city by city type and total rides per city type.

![ride_count_data](https://github.com/Wall-E28/pyBer_analysis/blob/master/analysis/Fig2.png)
![total_ride_data](https://github.com/Wall-E28/pyBer_analysis/blob/master/analysis/Fig6.png)

### Drivers per City Type

Drivers per city type is broken up into two different categories: drivers per city by city type and total drivers per city type.

![driver_count_data](https://github.com/Wall-E28/pyBer_analysis/blob/master/analysis/Fig4.png)
![total_driver_data](https://github.com/Wall-E28/pyBer_analysis/blob/master/analysis/Fig7.png)

### Fares per City Type

Fares per city tpes is broken up into three different categories: average fares per city by city type, total fares per city type, and weekly totals per city type.

![avg_fare_data](https://github.com/Wall-E28/pyBer_analysis/blob/master/analysis/Fig3.png)
![total_fare_data](https://github.com/Wall-E28/pyBer_analysis/blob/master/analysis/Fig5.png)
![weekly_fare_data](https://github.com/Wall-E28/pyBer_analysis/blob/master/analysis/PyBer_fare_summary.png)

## Summary

Based on the results listed above, I have come up with three different recommendations to address the disparities among the city types.

1. Since rural city types make up 5.3% of rides (Fig6) and 6.8% of fares (Fig5), but only have 2.6% of drivers (Fig7). We should attract more drivers by showing that on average they can make more per ride compared to the other city types (Fig3).

2. Similar to rural, suburban city types make up 26.3% of rides (Fig6) and 30.5% of fares, but only have 16.5% of drivers (Fig7). We should attract more drivers by showing they have the most consistent fares compared to the other city types (Fig3).

3. Oppisite to rural and suburban city types, urban city types only have 68.4% of rides (Fig6) and 62.7% of fares, but have 80.9% of drivers. We should attract more riders by showing that on average their fares are the lowest of any city type (Fig3).
