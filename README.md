# weather-appliction
Version: 1.0 <br>
Author: Avinash Rai <br>
Release: 23/06/2015 <br>

Weather Application is an one-page web application, developed and designed for displaying current and five-day-forecast weather data for a single location. This application uses two APIs :- <a href="http://openweathermap.org/api">OpenweatherMapAPI</a> and <a href="http://www.telize.com/">Telize GeoIP API</a>.

<h3>Features</h3>

1. The application uses Telize GeoIP to find the user's geo co-ordinates and use to it to call the weather information from OpenWeatherMap API.
2. The user's can search for a location, by entering the location's name on the application's Autocomplete search feature. Selecting the location will display its weather information.

<h3>Setup Instructions</h3>

1. You will need to first get an Application Key from <a href="http://openweathermap.org/api">OpenWeatherMap.</a>. <br><strong>Note this is not a product placement scheme and there are other alternatives for this. However this will require changes in "config.php" file and may require changes in the "view" files.</strong>
2. In the "application/config.php" file, set the value <strong>'APPID' =>  </strong>, with the new accquired Application key.
3. Place all folders in a desired location.
4. Run the application, by setting the URL Pointer to the "public" folder. E.g. <i> http://localhost/weather-application/public/</i>
