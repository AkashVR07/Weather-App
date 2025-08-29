# Weather-App
A simple, user-friendly weather application built with Python, KivyMD, and WeatherAPI. Enter a city name to get real-time weather information, displayed on the UI and spoken aloud using text-to-speech.

# Features
* Real-Time Weather Data: Fetches current weather details including temperature, condition, humidity, and wind speed.
* Text-to-Speech: Weather information is narrated aloud using the ```pyttsx3``` library.
* Responsive UI: Built with KivyMD for a modern, Material Design-inspired interface.
* Error Handling: Gracefully handles invalid inputs, network issues, and API errors.

# Prerequisites
Before running the app, ensure you have the following installed:
* Python 3.x
* A WeatherAPI key (sign up at WeatherAPI to get your free API key)

# Usage
1. Run the App: ```python weather_app.py```
2. Interact with the App:
* Launch the app to see a simple interface.
* Enter a city name (e.g., "London") in the text field.
* Click the "Get Weather" button to fetch and display the weather data.
* Listen as the weather details are spoken aloud.

# Dependencies
* ```kivy```: For the app’s graphical interface.
* ```kivymd```: For Material Design components.
* ```requests```: To fetch weather data from the WeatherAPI.
* ```pyttsx3```: For text-to-speech functionality.

# Snapshot
<img width="1001" height="788" alt="Snapshot" src="https://github.com/user-attachments/assets/79853623-facf-41f7-b0fb-0e5f65be7c24" />

# Example Output
Upon entering "Bangalore":\
City: Bangalore\
Temperature: 28.2°C\
Condition: Partly cloudy\
Humidity: 58%\
Wind Speed: 15.8 km/h\
The app will also narrate: ***"The weather in Bangalore is partly cloudy. The temperature is 28.2 degrees Celsius, with 58 percent humidity, and wind speed of 15.8 kilometers per hour."***


