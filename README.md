# World Weather Analysis

## Overview 
The purpose of this assignment was to retrieve weather data and to create a customer travel destination map. 

I used the numpy random module to generate random latitude and longitude locations. I used citypy to find the nearest city.

Using the OpeWeather API, I found data about those cities - weather, max temp, etc. Then I requested destinations between 50 and 80 degrees. 

Then using Google Maps API, I was able to find hotels at those locations and retrieve JSON data.

I came up with 4 destinations in France, and plotted my route on a map. The starting and ending points were the same, and I had 3 destination stops. Each marker showed a Hotel Name, City, Country and Current Weather.