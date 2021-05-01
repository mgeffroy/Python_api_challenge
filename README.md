# Python_api_challenge
## Information:
What's the weather like? API made for weather visualization of 500+ cities across the world. It allows looking for weather data and you can narrow your results to find your perfect vacation spot depending on local weather.It uses information from the Open Weather API, and with the Google Places API you can search for hotels in the city that has the perfect weather conditions of your curated list.
##**WeatherPy** 
Main repository divided in three main ones: 
### Weather :sun_behind_small_cloud::cloud_with_snow::cloud::sunny:
This repository contains the following elements:  
- ***Weatherpy.ipynb:*** Script to get information from the API and converting it into a dataframe, cleaning information and then analysing weather data. Temperature, Humidity, Cloudiness and Wind Speed and their relationships with Latitude was analysed and plots were created. The dataframe was later divided with diviing data into cities belonging to the south and north hemisphere were it was analysed and scatterplots with a correlation and regression analysis where made. With this script the following images were created: 
  - Latitude vs Max Temperature (**sp_latitude_vs_maxtemp.png**)
  
![sp_latitude_vs_maxtemp](https://user-images.githubusercontent.com/79372976/116792651-9e6a3700-aa87-11eb-8ff7-69d739594389.png)
  
  
  - Latitude vs Humidity (**sp_latitude_vs_humidity.png**)
  
![sp_latitude_vs_humidity](https://user-images.githubusercontent.com/79372976/116793026-e7bb8600-aa89-11eb-9d29-055114ad0019.png)

  
  - Latitude vs Wind speed (**sp_latitude_vs_wind.png**)
  
![sp_latitude_vs_wind](https://user-images.githubusercontent.com/79372976/116792709-f6a13900-aa87-11eb-84b6-e84fd88199bf.png)
 
 
  - Latitude vs Cloudiness (**sp_latitude_vs_cloudiness.png**)
  
![sp_latitude_vs_Cloudiness](https://user-images.githubusercontent.com/79372976/116792732-1df80600-aa88-11eb-841b-67713c5a0b4c.png)

  - Northern Hemisphere - Temperature (F) vs. Latitude (**N_vs_maxtemp.png**)
  - Southern Hemisphere - Temperature (F) vs. Latitude (**S_vs_maxtemp.png**)
  - Northern Hemisphere - Humidity (%) vs. Latitude (**N_vs_humidity.png**)
  - Southern Hemisphere - Humidity (%) vs. Latitude (**S_vs_humidity.png**)
  - Northern Hemisphere - Cloudiness (%) vs. Latitude (**N_vs_cloudiness.png**)
  - Southern Hemisphere - Cloudiness (%) vs. Latitude (**S_vs_cloudiness.png**)
  - Northern Hemisphere - Wind Speed (mph) vs. Latitude (**N_vs_windspeed.png**)
  - Southern Hemisphere - Wind Speed (mph) vs. Latitude (**S_vs_windspeed.png**)  
 

### Output
-**cities.csv**: CSV file that contains the clean and summarized information about weather in more than 500 cities. 
### Vacation :palm_tree:
- ***Vacation.ipynb:*** Script that uses weather data for future vacacion planning. Perfect weather conditions were chosen and jupyter-gmaps and Google places API was used to find a hotel in chosen cities. 
- ***map.png***: Map shows the heatlayer and also bullet points of the chosen hotels for a perfect vacation. 
![map](https://user-images.githubusercontent.com/79372976/116792969-94493800-aa89-11eb-84bb-48787b9dc78a.png)



*This was created by: Mariana Geffroy*
*for the Tecnológico de Monterrey Data Analysis Bootcamp*
