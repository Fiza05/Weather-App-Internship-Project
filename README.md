# Weather App - Java Swing & AWT

A simple weather application built with Java, using Swing and AWT for creating the User Interface (UI). The application fetches weather details using the OpenWeather API and displays them in a tabular format. It also includes a custom combo box for auto-completing city names based on user input.

## Features

- **Java Swing & AWT UI**: The UI is developed using Java Swing and AWT components to provide a clean, responsive, and user-friendly interface.
- **Weather Data**: Fetches real-time weather information using the OpenWeather API.
- **Tabular Display**: Displays the weather details in a tabular UI format for easy viewing.
- **Auto-complete Combo Box**: A custom combo box is implemented to suggest city names based on user input. It matches the input with the nearest city names from a JSON file containing a list of cities.
- **City Data from JSON**: The city names are loaded from a JSON file that was downloaded from the OpenWeather API website.

## How It Works

- **UI**: The application uses Java Swing and AWT to create the graphical user interface. The main window contains a custom combo box for city selection and a table to display weather details.

- **City Selection**: The custom combo box allows users to start typing a city name. It automatically suggests the nearest matching city names using the JSON file as the data source.

- **Fetching Weather Data**: When a city is selected, the application makes an API call to OpenWeather to fetch the current weather details.

- **Displaying Data**: The weather information, such as temperature, humidity, and weather conditions, is displayed in a table format.
