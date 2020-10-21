# Communicate Data Findings: RITA Flight Data in 2008
## by HyunGyung Lee


## Dataset

This dataset reports flights in the United States, including carriers, arrival and departure delays, 
and reasons for delays in 2008.
The data comes originally from RITA.
Downloaded source is https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7. 

Datasets used in this project:
    1. `2008.csv` : Main dataset to anlayze
    2. `airports.csv` : Describes the international airport abbreviation code name of the airport
    3. `carriers.csv` : Listing of carrier codes with full names
    4. `plane-data.csv` : Information about some individual planes


## Summary of Findings

The results of the relationship between the two variables are as follows:

- Delays in departure and arrival are correlated. But the stregth is weak.
- Delay time and distance are not correlated
- Delay time and AirTime are not correlated either.
- The difference of the delay time according to the day of the week is not that significant. 
- However, analysis shows that delays occur most frequently on Friday.
- Beech is the manufacturer with the most departure delay, and Southwest Airlines Co. is the airline.
- Douglas is the manufacturer of the most arrival delay, and Frontier Airlines Inc. is the airline.


## Key Insights for Presentation

For the presentation, I focus on the arrival delay time by manufacturer and airline through the heat map.
First of all, it was the earliest arrival time when it was the airplane of Airbus Industries carried by US Airways Inc. 
In other hands, longest arrival delays was shown by Frontier Airlines.Inc, which operates planes manufactured by Airbus Industries.
It is interesting that even airplanes made by the same manufacturer have different delays depending on carriers.
The project showed that manufacturers and carriers have a differenct effact on late arrival(or departure) of airplanes.