# Weather Wonders: An Api Journey from Data Analysis to Dream Vacations

## Project Overview 
This project demonstrates the use of APIs to analyze weather data and plan vacations based on ideal weather conditions. It is divided into two main parts: WeatherPy and VacationPy.

**WeatherPy:**
Visualizes the weather of over 500 cities of varying distances from the equator to understand the relationship between weather variables and latitude.

**VacationPy:**
Uses weather data to plan future vacations, visualizing ideal locations based on preferred weather conditions.


## Part 1: WeatherPy

### Objective
To visualize the weather of over 500 cities of varying distances from the equator and analyze the relationship between latitude and weather variables.

**Steps Taken**

 1. **Generated Random Coordinates:**
 Used the provided code to generate random geographic coordinates and found the nearest cities.

 2. **Retrieved Weather Data:**
Used the OpenWeatherMap API to get weather data for the cities.

 3. **Created Scatter Plots like following:**

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

## Compute Linear Regression:
For each relationship, computed linear regression and created scatter plots for the Northern and Southern Hemispheres:

- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

## Findings
Provided detailed explanations for each plot, describing any noticeable trends and relationships.

## Part 2: VacationPy

### Objective
To use weather data to identify ideal vacation spots and find nearby hotels.

**Steps Taken**

1. Created Humidity Map:
Displayed a point for every city in the city_data_df DataFrame with point size representing humidity.

2. Filtered Ideal Weather Conditions:
Narrowed down the DataFrame to find cities with ideal weather conditions (e.g., temperature, wind speed, cloudiness).

3. Found Nearby Hotels:
Use the Geoapify API to find the first hotel within 10,000 meters of each city's coordinates.

4. Created Vacation Map:
Display a map with hover messages showing the city, country, and hotel name.


## Applications

**WeatherPy Applications:**
- **Climate Research:** By understanding the relationship between latitude and various weather parameters, researchers can study climate patterns and changes over time.

- **Urban Planning:** City planners can use weather data to make informed decisions about infrastructure and urban development based on climatic conditions.

- **Agriculture:** Farmers and agricultural businesses can plan crop cycles and management practices based on weather trends.

2. **VacationPy Applications:**

- **Tourism Industry:** Travel agencies and tourism boards can use weather data to recommend optimal vacation spots based on travelers' preferred weather conditions.

- **Travel Planning:** Individuals can plan vacations around ideal weather conditions, ensuring a more enjoyable and comfortable experience.

- **Hotel Industry:** Hotels can leverage this data to promote their locations during periods of favorable weather, attracting more guests.

## Conclusion
This project showcases the powerful combination of data analysis and API integration to derive actionable insights. By visualizing weather data and identifying optimal vacation spots, it demonstrates practical applications that can benefit various industries, from tourism to agriculture. The findings from this project highlight the importance of weather data in decision-making processes, offering valuable information for planning and optimizing various activities.








