Gaia'sMoodToday

A simple weather application that displays the current weather and forecast for a given city.

![Gaia'sMToday Screenshot](![Alt text=A screenshot of Gaia's Mood Today, a weather forecast website displaying the current temperature, wind speed, and humidity for Tifton, Georgia as well as the 5-day forecast for the city. The website features a search bar and dropdown menu for users to search for weather information for other cities. ](script src: "assets/Gaia-sMoodTodayscreenshot.png")

## Structure

1. **Header**: The header of the application contains the title "Gaia'sMoodToday".

2. **Aside**: The aside section contains a form to search for a city and displays a list of previous searches.
   - **Form**: The form has a single input field for the city name and a submit button.
   - **History**: The history section displays a list of previous searches, allowing users to quickly access weather information for cities they've searched for before.

3. **Main**: The main section contains two sections: today's weather and the forecast.
   - **Today**: The today section displays the current weather information for the selected city.
   - **Forecast**: The forecast section displays the weather forecast for the next few days.

4. **Scripts**: The application uses Day.js, a lightweight JavaScript library for manipulating and formatting dates, to display the weather information. The custom script.js file handles user interactions and API calls.