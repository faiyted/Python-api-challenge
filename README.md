# Python-api-challenge

# Instructions - Part 1: WeatherPy

** Create Plots to Showcase the Relationship Between Weather Variables and Latitude
** To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

  - Latitude vs. Temperature

  - Latitude vs. Humidity

  - Latitude vs. Cloudiness

  - Latitude vs. Wind Speed

** Compute Linear Regression for Each Relationship
** To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots. Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r^2 values as you can see in the following image

   ![image](https://github.com/user-attachments/assets/5ba2e00e-d470-423d-9a17-145f7d427399)

** Create the following plots:

  - Northern Hemisphere: Temperature vs. Latitude
  
  - Southern Hemisphere: Temperature vs. Latitude
  
  - Northern Hemisphere: Humidity vs. Latitude
  
  - Southern Hemisphere: Humidity vs. Latitude
  
  - Northern Hemisphere: Cloudiness vs. Latitude
  
  - Southern Hemisphere: Cloudiness vs. Latitude
  
  - Northern Hemisphere: Wind Speed vs. Latitude
  
  - Southern Hemisphere: Wind Speed vs. Latitude

** After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

# Instructions - Part 2: VacationPy

** Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

  ![image](https://github.com/user-attachments/assets/4c1afdaa-e17b-4fb7-9356-6935cc03629d)

** Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

  - A max temperature lower than 27 degrees but higher than 21

  - Wind speed less than 4.5 m/s

  - Zero cloudiness

** Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
** For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
** Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:

  ![image](https://github.com/user-attachments/assets/a585cf6b-7fff-4779-9f7f-bcd4753c585d)



