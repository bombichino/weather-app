# Weather Dashboard

This app sets up a weather dashboard that calls the current weather and forecast for the next 5 days for any city you search for. It also stores the recent search history from your current and previous sessions.

## Continued improvements

-The site currently adheres to the requitement that, upon loading, the recent search history is displayed. However, I would like to get it to stick and be added to by the new searches rather than replaced by a new search. I know this has to do with the placement of "var cityHistory = []" but I'm not sure how to circumvent it.

## Assignment Criteria

GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
WHEN I open the weather dashboard
THEN I am presented with the last searched city forecast