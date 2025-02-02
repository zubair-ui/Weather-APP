# Weather Application (Python + Tkinter)

## Description

This **Weather Application** fetches real-time weather data from the **OpenWeatherMap API** and displays it in a **Tkinter** GUI. The user can input any city name, and the app will display the current weather, including temperature, humidity, condition, wind speed, and more.

## Features

- **Simple and clean interface** built with Tkinter.
- Fetches **real-time weather data** from the OpenWeatherMap API.
- Displays key weather details:
  - Temperature (°C)
  - Humidity (%)
  - Condition (e.g., Clear, Rainy)
  - Wind Speed (m/s)
  - Feels Like temperature (°C)
- **Error handling** to notify the user if the city is not found or there is an API issue.

## Installation

### Prerequisites

- **Python 3.x** installed on your system.
- **Tkinter** for GUI (usually comes with Python).
- **Requests** library for making HTTP requests to the OpenWeatherMap API.

### Step-by-Step Guide

1. **Clone the repository**:

   ```bash
   git clone https://github.com/zubair-ui/Weather-APP.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd weather-app
   ```

3. **Install the required libraries**:
   Make sure you have `requests` installed. Run:

   ```bash
   pip install requests
   ```

4. **Get an API Key**:
   - Sign up at [OpenWeatherMap](https://openweathermap.org/api) to get a **free API key**.
   - Replace `open("API key.txt",'r').read` in the code with your own API key or the name of the file in which you stored the key.

## Usage

1. **Run the application**:

   - Open a terminal and navigate to the project folder.
   - Run the Python script:
     ```bash
     python weather_app.py
     ```

2. **Enter a city name** in the input field and click **Get Weather**.
3. The weather information (Temperature, Humidity, Condition, Wind Speed, and Feels Like) will be displayed below.

## Acknowledgements

- [OpenWeatherMap API](https://openweathermap.org/api) for providing real-time weather data.
- [Tkinter](https://wiki.python.org/moin/TkInter) for the graphical user interface.
