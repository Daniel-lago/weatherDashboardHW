# Weather Dashboard

A web-app for checking the current weather and 5-day forecast for a city.


## Contents

1. [About](#about)
    1. [User Story](#user%20story)
    2. [Acceptance criteria](#acceptance%20criteria)
    3. [Visuals](#visuals)
    4. [Data](#data)
    5. [Build](#build)
2. [Site Location](#site%20location)
3. [Contributing](#contributing)

### About

Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. Your challenge is to build a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.

### User Story

    AS A traveler
    I WANT to see the weather outlook for multiple cities
    SO THAT I can plan a trip accordingly

### Acceptance Criteria

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


### Usage:

![Screenshot of load page](./Assets/Forecast.jpg)

This is the main page for the aplication, in this we can found on the left side two elements, at the top the search bar, in the which one we'll type for the city we are looking for.

![Usage of the page components](./Assets/SearchBAr.png)

And at the bottom the history of the places we already search for. 

![Usage of the page components](./Assets/Historial.jpg)



## Data

The application uses the following data inputs:
* Weather information is provided by the OpenWeather [OpenWeatherMap API](https://openweathermap.org/). [Documentation](https://openweathermap.org/api) can be found here


## Build

* In HTML semantic tags have been used to aid with accessibility. 
* In CSS to bring a user the best visual experience
* In Javascript to get all the information an the functions relative to the functionallity. 
* [moment.js](https://momentjs.com/) is used to manipulate date values for historic data extraction from APIs



## Site Location
[Weather Dashboard ](https://daniel-lago.github.io/weather-dashboard-hw/)

### Contributing
Made by [Daniel-lago](https://github.com/Daniel-lago)



### ©️2022 Daniel Lago
