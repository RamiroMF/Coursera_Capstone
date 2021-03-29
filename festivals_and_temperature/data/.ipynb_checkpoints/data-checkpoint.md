In this analysis we will use mean monthly temperatures extracted from [Wikipedia](https://en.wikipedia.org/wiki/List_of_cities_by_average_temperature) and foursquare data of festivals in the different locations.

For the temperatures, I will extract the data using BeautifulSoup and create a Pandas Dataframe. I will later use KNN clustering to cluster the data based on temperatures. In the last step I will get the number of festivals per location in a 10 Km radius and check if there is any correlation to the different clusters.

![alt text](temps_city.png "cities")