# Analysis of ridesharing fare volume by city type

## Project Overview

Part of a larger initiative to analyze ridesharing data by city type.  Cities are categorized as either Urban, Suburban, or Rural based on the size of the city.

## Resources
* Anaconda3 (2021.11)
* Jupyter Lab (3.2.1)
* Python (3.7.11)
    * Pandas module (1.3.4)
    * Numpy module (1.20.3)
    * citiPy 0.0.5
    * matplotlib (3.4.3)
    * requests library (2.26.0)
* Visual Studio Code (1.63.2)

## The Data

* city data `city_data.csv`
    * Columns:
        * city
        * driver count
        * type (Urban/Suburban/Rural)

* ride data `ride_data.csv`
    * Columns:
        * City
        * Date (timestamp of ride)
        * fare ($USD)
        * ride_id (unused in analysis)

## Analysis

Numer of rides per city type is wildly disparate with considerably larger volume in cities.

![Figure 9 -- Table of aggregate statistics by city type](Analysis/Fig9.png)
![Figure 8 -- Chart of total fares by city type](Analysis/Fig8.png)

This is a consistent pattern across cities.  Number of rural drivers are far below even number of suburban drivers.
![Figure 2 -- Number of rides by city per city type](Analysis/Fig2.png)

Look at this!
![Figure 1 -- bubbles.](Analysis/Fig1.png)

## Recommendations

* Hire more drivers in rural areas.  Average wages per driver are high and could be used as an incentive.
* Market more heavily in rural areas
* Consider disparate causes/patterns among rides.  Rural rides likely more expensive on average due to longer trips.
    *Intercity rides vs intracity rides