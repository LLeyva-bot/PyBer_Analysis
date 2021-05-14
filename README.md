# Module_Five_PyBer_Analysis

## Project Analysis
Perform an exploratory analysis using PyBer rideshare data to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.

1. Provide a summary of the ride-sharing data by city type: Rural, Suburban, and Urban. 
2. Provide a multiple-line graph showing the total weekly fares for each city type.
3. Provide business recommendations for addressing any dipsarities among the city types. 

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python, Jupyter Notebook, Pandas, Matplotlib

## Results
PyBer City Type Summary. 
![PyBer_city_type_summary.png](https://github.com/LLeyva-bot/PyBer_Analysis/blob/main/Analysis/PyBer_city_type_summary.PNG)
- Rural City Types
  - Total Rides:  Rural cities have the _lowest_ total at 20% of the total rides of Suburban cities and 8% of the total rides Urban cities.
  - Total Drivers: Rural cities have the _lowest_ total at 16% of the total drivers of Suburban cities and 3% of the total drivers of Urban cities.
  - Total Fares: Rural cities have the _lowest_ total at 22% of the total drivers of Suburban cities and 11% of the total drivers of Urban cities.
  - Average Fare per Ride: Rural cities have the _highest_ average at 112% of average fare per ride of Suburban cities and 141% of the average fare per ride of Urban cities. 
  - Average Fare per Driver: Rural cities have the _highest_ average at 140% of the average fare per driver of Suburban cities and 335% of the average fare per driver of Urban cities.
- Suburban City Types
  - Total Rides: Suburban cities fall in between at 38% of the total rides of urban cities and 500% of the total rides of Rural cities.
  - Total Drivers: Suburban cities fall in between at 20% of the total drivers of urban cities and 628% of the total drivers of Rural cities.
  - Total Fares: Suburban cities fall in between at 49% of the total fares of urban cities and 447% of the total fares of Rural cities.
  - Average Fare per Ride: Suburban cities fall in between at 126% of the average fare per ride of urban cities and 90% of the average fare per ride of Rural cities. 
  - Average Fare per Driver: Suburban cities fall in between at 238% of the average fare per driver of urban cities and 71% of the average fare per dirver of Rural cities.
- Urban City Types
  - Total Rides:  Urban cities have the _highest_ total at 260% of the total rides of Suburban cities and 1300% of the total rides of Rural cities.
  - Total Drivers: Urban cities have the _highest_ total at 491% of the total drivers of Suburban cities and 308% of the total drivers of Rural cities.
  - Total Fares: Urban cities have the _highest_ total at 206% of the total fares of Suburban cities and 921% of the total fares of Rural cities.
  - Average Fare per Ride: Urban cities have the _lowest_ average at 79% of the average fare per ride of Suburban cities and 71% of the average fare per ride of Rural cities. 
  - Average Fare per Driver: Urban cities have the _lowest_ average at 42% of the average fare per driver of Suburban cities and 30% of the average fare per dirver of Rural cities.

PyBer Weekly Total Fares by City Type - Displays fares from January 1, 2019 up to April 29, 2019.
![PyBer_fare_summary.png](https://github.com/LLeyva-bot/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)
- The multi-line graph supports our PyBer City Type Summary results.  Urban cities hold the _highest_ weekly total of fares, Suburban cities are in the _middle_, and Rural cities have the _lowest_ weekly total of fares. They do not intersect at any point.  
- All city types experience a spike in weekly fares towards the second week of February. Urban and Rural cities experiense an immeditate drop until May while Urban cities experience a gradual drop and then an immediate spike in weekly fares the first week of May.  This indicates Urban cities have more buisness wihtin that time frame. 

## Summary
Rural city types have the _lowest_ total of rides, drivers and fares while maintaining the _highest_ average fare for drivers and rides.  The highest average fare per ride may be bringing down the demand for rides.  The lack of demand could be the reason for the lack of drivers.  A recommendation for this disparity is to aquire more riders in rural areas.  Increasing the demand will attract more drivers and increase total fares in Rural cities. 

Urban city types have the _highest_ total of rides, drivers and fares, yet have the _lowest_ average fare for drivers and rides.  Drivers are attracted to Urban cities due to the demand and have oversaturated the market. The oversatruation has brought down the average fares for drivers because there are more drivers than rides.  A recommendation for this disparity is to push Urban drivers towards Suburban and Rural cities by educating drivers about the oversaturation and the average fares per ride are higher in Suburban and Rural cities.

Suburban city types fall in between Urban and Rural city types in every category.  Within the first four months of 2019, Suburban cities were somewhat consistant in total fares week to week.  However, Suburban cities only have 38% of the total rides of Urban cities.  This disparity can be improved by aquiring more riders.  Temporary lowering the fares in Suburban cities to match Urban cities may create a demand for rides and increase the total fares. 
