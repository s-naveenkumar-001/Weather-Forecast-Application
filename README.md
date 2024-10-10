# Weather Forecasting App 🌤️

This **Weather Forecasting App** is a desktop application built using Python and Tkinter for the GUI. The app fetches real-time weather information based on the user's input for any city around the world, using the OpenWeatherMap API.

## Features
- Displays the current weather for any city by entering the city name.
- Shows temperature, weather conditions, wind speed, humidity, pressure, and a brief description of the weather.
- Real-time clock with the current local time of the specified city.
- User-friendly graphical interface with a search bar and icons.

## Technologies Used
- **Python**: Core programming language.
- **Tkinter**: Used for creating the graphical user interface (GUI).
- **Geopy**: To fetch geographical information based on the city.
- **TimezoneFinder**: To find the correct timezone of the city.
- **Requests**: To make API requests to fetch the weather data.
- **OpenWeatherMap API**: External API to get weather data.
- **Pytz**: For accurate timezone handling.

## Requirements
To run this project, ensure you have the following Python libraries installed:

```bash
pip install tkinter geopy timezonefinder requests pytz
```

## Setup Instructions
1. Clone the repository or download the project files.

    ```bash
    git clone https://github.com/s-naveenkumar-001/Weather-Forecast-Application.git
    cd Weather-App-GUI
    ```

2. Obtain your free API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) and replace the API key in the following line of the code:

    ```python
    api = "https://api.openweathermap.org/data/2.5/weather?q=" + city + "&appid=YOUR_API_KEY"
    ```

3. Ensure that the following image files are in the same directory as the script:
   - `logo.png`
   - `search.png`
   - `search_icon.png`
   - `box.png`

4. Run the `weather_app.py` script to launch the app.

    ```bash
    python weather.py
    ```

## How to Use
1. Enter the name of the city for which you want to know the weather in the search bar.
2. Press the search icon or hit Enter to get the current weather information.
3. The app will display the following information:
    - Current temperature
    - Weather condition
    - Wind speed
    - Humidity
    - Pressure
    - Weather description
    - Local time of the city

## Output Screenshots

### Example 1: Get Lagos Weather Details

![Lagos Weather](https://github.com/s-naveenkumar-001/Weather-Forecast-Application/blob/main/Weather-App-GUI/Weather-app.jpg)

### Example 2: Weather Details of Lagos

![Lagos Weather](https://github.com/s-naveenkumar-001/Weather-Forecast-Application/blob/main/Weather-App-GUI/Weather-app2.jpg)
