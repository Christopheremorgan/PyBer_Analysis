# PyBer_Analysis

## Analysis Overview
PyBer is a ride-sharing app company valued at $2.3 billion. This project analyzes rideshare data from January to early May of 2019 with a focus on creating compelling visualizations for the CEO, V. Isualize.  This exploratory analysis will be used to improve ride sharing access and determine affordability for underserved communities.  City and ride data were shared via csv files and analyzed using Python with Pandas and Matplotlib packages. 


## Results
As expected, the demand for ride sharing is highest in urban cities and lowest in rural cities.  Conversely, the average fare per ride is highest for rural cities and lowest for urban cities.  One interesting observation is that there are more drivers than total ride demand in urban cities for the four month period observed.


![image_name](https://github.com/Christopheremorgan/PyBer_Analysis/blob/main/analysis/Pyber_Dataframe_Summary.png)

Although there are some comparable volume trends that play out across the 3 city types, two additional peaks are observed in March in urban cities that are not observed in rural and surburban cities.  We also see that the total fare for urban cities is roughly twice that of suburban cities and more than 5 times that of rural cities.

![image_name](https://github.com/Christopheremorgan/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
Based on the results, driver supply does not seem to be an issue and there is enough driver capacity for agressive growth and demand driving tactics.  A key item missing to understand affordability for each city type is the total population of each city.   By adding population we can get a better sense of capture for each city and the potentially underserved communities within each city type.  This would also provide an idea for potential growth opportunities.  

In addition, having the distance travelled for each ride would allow us to understand better if the higher average fares for suburban and rural cities are driven by total distance travelled by drivers.   By having total distance along with the time to respond to the rider request we can get a better idea of whether we have an opportunity to adjust driver assignment logic or for implementing more variable or scalable rates.

One other piece of information that may be helpful is marrying volumes to an event calendar to identify if events may be driving demand peaks in March for the urban communities where the events occur.  This may signal future opportunities to increase urban rates during specific events.
