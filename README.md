# python-api-challenge
This activity is broken down into two deliverables, WeatherPy and VacationPy. Both will require API keys to complete
Part 1: WeatherPy
Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Plot series of scatter plots to showcase the following relationships:
  Latitude vs. Temperature
  Latitude vs. Humidity
  Latitude vs. Cloudiness
  Latitude vs. Wind Speed
Requirement 2: Compute Linear Regression for Each Relationship
You should create the following plots:
  Northern Hemisphere: Temperature vs. Latitude
  Southern Hemisphere: Temperature vs. Latitude
  Northern Hemisphere: Humidity vs. Latitude
  Southern Hemisphere: Humidity vs. Latitude
  Northern Hemisphere: Cloudiness vs. Latitude
  Southern Hemisphere: Cloudiness vs. Latitude
  Northern Hemisphere: Wind Speed vs. Latitude
  Southern Hemisphere: Wind Speed vs. Latitude
Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.
Create a map that displays a point for every city in the city_data DataFrame as shown in the following image. The size of the point should be the humidity in each city.
Reduce the city_data DataFrame to find your ideal weather condition. 
•	A max temperature lower than 27 degrees but higher than 21
•	Wind speed less than 4.5 m/s
•	Zero cloudiness
Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:


