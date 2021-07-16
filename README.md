# PyBer_Analysis

## Overview
The purpose of this analysis was to summarize ride-sharing data by city type to better examine trends at the city level. By creating a city type summary DataFrame and graphing total fares by city, we can provide PyBer with knowledge that they can utilize when making business decisions in varying locations.

## Results
By looking at both the city type summary DataFrame and the "Total Fare By City Type" graph below, one can see that from the data given:
- Urban cities have the most rides, drivers, and total fares
- Suburban cities have the 2nd most rides, drivers, and total fares
- Rural cities have the least rides, drivers, and total fares
- Urban cities have the lowest average fare per ride and per driver
- Suburban cities have the 2nd lowest average fare per ride and per driver
- Rural cities have the highest average fare per ride and per driver

![df](https://github.com/typicalchazz/PyBer_Analysis/blob/main/analysis/City_Type_Summary_df.png)

![graph](https://github.com/typicalchazz/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
The results of our data show some interesting trends: as one moves away from denser urban areas, such as the suburbs or rural areas, there are less available drivers and less rides are given, but average ride and driver fares increase. These trends are understandable. Given that cities are more dense, that usually means there is a higher density of cars, meaning more ride-sharers available to offer rides. Since cities are dense, the distance to travel between any two places is likely to be shorter than that of other areas, making trips be less expensive than other areas. As you leave the city center and enter the suburbs and rural areas, the population is less dense, meaning there are less ride-sharers available to offer rides, and distances between places are greater, making ride fares more expensive on average. Given these trends, I would make a few recommendations to PyBer:
1. Increase the cost per mile for rides in urban areas to balance out driver fare averages.
2. Decrease the cost per mile for rides in rural areas to incentivize people to use PyBer in rural areas.
3. Increase the number of drivers in rural and surburban areas. According to the data provided, there are more drivers available for ride-sharing in urban areas than there were rides given, meaning that there are drivers that are enrolled in PyBer's ride sharing but didn't give any rides. The data provided shows that there were more rides than drivers in rural and suburban communities, meaning there may be more than enough rides to go around. Urban drivers who aren't getting driving opportunities should be sent to rural and suburban communities.