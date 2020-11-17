# PyBer_Analysis

## Overview of the Analysis

### Purpose
The purpose of this analysis was to create a summary DataFrame of the ride-sharing data by city type. Based on the results, a multiple-line graph was created to that show the total weekly fares for each city type. Finally, the summary that explains how the data differs by city type and how any disparities can be brought forth to the CEO to improving the business.

## Results 
Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. The results were found using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns. Doing so calculated the total number of rides, total number of drivers, the total fares, the average fare per ride and average fare per driver for each city type. Finally, the data was put into a new DataFrame.
- Based on the results below, it is apparent that the majority of the rides, drivers, fares come from urban cities. Urban cities make up more  60% of the total rides, total drivers, and total fares.
    - ![]()
    - ![]()
    - ![]()
- Although the number of rides are low in rural cities, the average fare per ride and driver are higher in comparison to other cities. The cause of the higher average is probably due to the fact that rural shares are longer and scarce. The images below validate this assumption.
    - ![]()
    - ![]()
- The total fare by city type showcases that urban cities generate the most revenue; followed by suburban and rural cities. 
    - ![]()

## Summary

### Three Business Recommendations:
1. There are more drivers than riders in urban cities. It is suggested the urban drivers relocate to another city type or CEO invest money in marketing and advertisements to attract potential riders.
2. The drivers should consider relocating to rural cities at the end of Feburary and beginning of May when ride count are at its highest. Drivers can earn more as the average fare per driver are higher in rural cities.
3. Urban cities should continue to have a sufficient amount of drivers in the month of March in order to meet the high demands. 