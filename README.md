# weatherLOFI
https://misdemo.temple.edu/tuk81124/LofiWeatherAPI

For this API Project in MIS 2402, we created an application using two to three APIs. For my application I used the OpenWeatherAPI, Youtube iframe API, and Google Maps API.

My application pulls a lofi playlist from Youtube, and the lofi playlist is based on the weather of the city the user entered or the clicked location on the map. 

I used the OpenWeatherAPI to get weather conditions based on the user's enter city. For the map clicking, I used the Google Maps API. When a user clicks on a map, the map shows the latitude and longitude. I searched the city name and weather using the latitude and longitude values returned from Google Maps. 

There are five conditions that returns five possible recommendations.
Weather that 
  1. matches 'clear sky'
  2. includes 'clouds;
  3. includes 'rain'
  4. includes 'snow'
  5. matches 'thunderstorm'
