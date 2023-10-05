# Real estate prices in St. Petersburg

Data is provided from the website for the sale of apartments in St. Petersburg and nearby settlements. 
We need to learn how to determine the price of property depending on the given data. 
In future projects, this will help predict fraudulent activity.

Purpose of the study: Determine which factors most influence the price of apartments

# Brief report

__Preprocessing__

Gaps in data were replaced, where possible, with median values. 
Gaps in the data on the distance to the nearest pond, park, airport, city center were left. 
Other missing data were removed. The dataframe was cleared of outliers by practical considerations. 
Thus, data on ceilings below 2.4 meters was removed because it does not meet the construction requirements for residential buildings. 

__EDA__

The most data is in the range from 30 to 50 sq.m., which correspond to prices from 3 to 5 million. 
Living area and kitchen area have a moderate impact on property value.

There is a trend towards increasing prices. 
From late 2014 to mid-2019, the median price per square meter rose from 90,000 to 100,000. 
The median price per square meter decreases depending on the number of rooms. 
Prices per sq.m. depend slightly on the number of floors in the house or the floor of the apartment itself. 
Apartments on the first and last floor are usually cheaper.

In cities with the greatest supply, the cheapest real estate is in Vsevolzhsk and Gatchina, the most expensive is in St. Petersburg. 
Half of the properties are sold within 3 months of an advertisement
