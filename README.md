# Challenge5

## Overview of the analysis
Explain the purpose of the new analysis.

Pyber is a ride-sharing app company valued at $2.3 billion with a presence in different type of cities: Urban, Suburban, Rural

![Graph1](https://github.com/Markov1987/Challenge5/blob/e33a4abe10523717b720cef61438669467897cd2/Resources/Graph1.png)


We have pulled rideshare data for 2019 and want to analyze some indicators per city type to understand differences and identify insights that may be useful for top management. 

For our analysis, we are retrieving the following indicators: 
- Total Rides. 
- Total Drivers.
- Total Fares. 
- Average Fare per Ride.
- Average Fare per Driver. 

Additionally, we'll add the information in weeks to identify trends at a Total Fare level. 

## Results

At a general level, retrieved information shows a higher penetration at Urban cities both for Total Drivers and Total Rides, althought, Average Fees are higher at Rural and Suburban cities:

![Graph2](https://github.com/Markov1987/Challenge5/blob/e33a4abe10523717b720cef61438669467897cd2/Resources/Graph2.png)

Is important to keep in mind although the 40% higher average fare from Rural to Urban Rides, over 60% of the total income comes from Urban Cities due to a 10 to 1 Total Rides among the city types. 


This can be seen at the total fare chart below: 

![Graph](https://github.com/Markov1987/Challenge5/blob/e33a4abe10523717b720cef61438669467897cd2/Analysis/Graph.png)

Note Urban Total Fare has some instability showing peaks and lows during March and seems to be the most volatile trend among the city types during 2019.


## Summary

Based on the data and trends analyzed before, we can provide the following recommendations: 

1) Urban is obviously our most important market, **we need to understand and, if possible, reduce the volatility seen last months**. We may need to study if this may be result of: Competition, Seasonality, Related to Holidans or any other social events, etc.  
2) Our penetration seems to be still low in Suburban and Urban cities, **higher average fees may be an indicator of a lower supply and/ or higher demand than market equilibrium.** As a result, driver's fees are higher in this types, if we are not able to recruit new drivers we may want to incentivize some Urban drivers to work in Suburban or Rural cities to catch this spread and help us to get those higher fees (lower drivers at Cities may also growth average fees there). 
3) If we need to focus on only one of the residual markets (Suburban & Rural) it seems better to start with Suburban independently that is not the higher average fees type. This recommendation relies in two facts: 1) There is a higher increase from Suburban to Urban fees than Rural to Suburban fees, this means we can catch most of the spread without moving to away from our current model. & 2) In the period, **total fares at Rural cities has been stable while Suburban total fares show a clear increase during the analysis period, this may means this is a market with higher growth potential**.  
