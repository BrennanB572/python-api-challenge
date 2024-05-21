# Python API Challenge
## ASU Data Aanlytics Bootcamp Module 6

## Instructions
- This activity is broken down into two deliverables, WeatherPy and VacationPy.

## Part 1: WeatherPy
- In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site., and your problem-solving skills to create a representative model of weather across cities.
- For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.
- To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
- To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

![image](https://github.com/BrennanB572/python-api-challenge/assets/114636599/06060b05-2deb-46da-8441-dd4b0de51832)

### Requirement 2: Compute Linear Regression for Each Relationship
- To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.
- Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image:

![image](https://github.com/BrennanB572/python-api-challenge/assets/114636599/0fd13ff0-9db6-44ab-b49d-4e953db8e2f3)

## Part 2: VacationPy
- In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.
- The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.
- Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.
- To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:
1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city:

![image](https://github.com/BrennanB572/python-api-challenge/assets/114636599/3c98c528-17ed-48e6-8657-7b6103602611)

2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

![image](https://github.com/BrennanB572/python-api-challenge/assets/114636599/005cb44d-c181-41a4-94ba-3acb8f8f5541)

3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:

![image](https://github.com/BrennanB572/python-api-challenge/assets/114636599/5f8f329d-6953-4046-950f-bfab013683ef)



