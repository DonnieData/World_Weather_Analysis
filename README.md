# World_Weather_Analysis
Utilizing python modules and API's to retrieve and analyze data to provide real-time suggestions. 

## Resources 
- Software: Python 3.7.6, JupyterLab 2.26
- [Google Cloud Platform, Google MapsAPIs](https://cloud.google.com/docs/?hl=en_US#section-6)
- [OpenWeatherMap API's](https://openweathermap.org/)

## Overview 
Creating python script for a hypothetical betaApp meant to provide hotel/lodging suggestions for a company based on user_end provided criteria.

[Weather_Database](https://github.com/DonnieData/World_Weather_Analysis/tree/main/Weather_Database)
- [numpy module](https://github.com/numpy/numpy) to generate 2,000 latitudes and longitude combinations 
- [Citypy](https://github.com/wingchen/citipy) to get the nearest city of latitude/longitude combination 
- OpenWeatherMap - to retrieve up-to-date weather data for the provided cities 

[Vacation_Search](https://github.com/DonnieData/World_Weather_Analysis/tree/main/Vacation_Search)
- The weather data from Weather_Database is parsed, formatted, and visualized with Google Maps API's.
- The focus of these visualizations are markers and up to date pop-up marker information displayed by category. 

[Vacation_Itinerary](https://github.com/DonnieData/World_Weather_Analysis/tree/main/Vacation_Itinerary)
- The same data from Vacation_Search is further filtered down by a "trip/itinerary" criteria. 
- This data is then visualized using Google's api. 
