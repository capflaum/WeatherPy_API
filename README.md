**WeatherPy**

A Python script is used to visualize the weather of 500+ cities across the world of varying distance from the equator. Using a simple Python library and the OpenWeatherMap API,  a representative model of weather across world cities is created with a series of scatter plots.


The following relationships are analyzed:

**Temperature (F) vs. Latitude**

Northern Hemisphere

![image](https://user-images.githubusercontent.com/69134400/119249895-3f14b980-bb51-11eb-9b77-fb8a8bd8907a.png)

Southern Hemisphere

![image](https://user-images.githubusercontent.com/69134400/119249901-4a67e500-bb51-11eb-8fee-7787752f96e5.png)


**Humidity (%) vs. Latitude**

Northern Hemisphere

![image](https://user-images.githubusercontent.com/69134400/119249966-b77b7a80-bb51-11eb-84fc-4c28a2d98401.png)

Southern Hemisphere

![image](https://user-images.githubusercontent.com/69134400/119249970-be09f200-bb51-11eb-8942-08e1196c2ed2.png)


**Cloudiness (%) vs. Latitude**

Northern Hemisphere

![image](https://user-images.githubusercontent.com/69134400/119249976-c6fac380-bb51-11eb-9f17-bfe89aff5a61.png)

Southern Hemisphere

![image](https://user-images.githubusercontent.com/69134400/119249983-d11cc200-bb51-11eb-9287-d7282b3fac47.png)


**Wind Speed (mph) vs. Latitude**

Northern Hemisphere

![image](https://user-images.githubusercontent.com/69134400/119249989-daa62a00-bb51-11eb-9b24-5baef3b1795f.png)

Southern Hemisphere

![image](https://user-images.githubusercontent.com/69134400/119249994-e134a180-bb51-11eb-8716-37717c90ac17.png)


After each plot add a sentence or too explaining what the code is and analyzing.
Your second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots explain what the linear regression is modeling such as any relationships you notice and any other analysis you may have.
Your final notebook must:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.


Part II - VacationPy
Now let's use your skills in working with weather data to plan future vacations. Use jupyter-gmaps and the Google Places API for this part of the assignment.


Note: Remember that any API usage beyond the $200 credit will be charged to your personal account. You can set quotas and limits to your daily requests to be sure you can't be charged. Check out Google Maps Platform Billing and Manage your cost of use for more information.


Note: if you having trouble displaying the maps try running jupyter nbextension enable --py gmaps in your environment and retry.


Create a heat map that displays the humidity for every city from the part I of the homework.



Narrow down the DataFrame to find your ideal weather condition. For example:


A max temperature lower than 80 degrees but higher than 70.


Wind speed less than 10 mph.


Zero cloudiness.




