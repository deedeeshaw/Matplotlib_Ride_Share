Ride Share Data Analysis Using Matplotlib

In this project I took two datasets in csv files; 'city_data' and 'ride_data'. The city_data file had the city name, driver count and city type (urban, rural, suburban) of 120 cities. The ride_data file had 2300+ records of ride share information; the city name, the date of the ride, fare, and ride ID.

Once the csv files were converted to data frames using pandas, the two data frames were merged on city name to create one data set. After that the data was separated into three data frames based on the city type i.e., urban, rural and suburban

These three data frames were used to create four graphs using Matplotlib.

1. A bubble plot displaying the total number of rides on the x-axis and the average fare on the y-axis. Different colors were used to differentiate the city types and the size of the bubbles correlated to the number of drivres.

2. A pie chart showing the percentage of total number of drivers in urban, rural and suburban cities.

3. A pie chart showing the percentage of total fares charged in urban, rural and suburban cities.

4. A pie chart showing the percentage total rides in urban, rural and suburban cities.

Analysing the charts it seems like;
* Ride sharing is most popular in the Urban cities and the average fare even in cities that have fewer drivers is not more than thirty dollars.

* The average fare of rides in rural cities can cost over forty dollars. However, this may not only be because of the scarcity of drivers in the rural cities and could be due to distances in rural cities.

* While the suburban city drivers make up only 16.5% of the total they take almost quarter of the total rides. Being a driver in a suburban city is better than being a driver in an urban or rural city.  