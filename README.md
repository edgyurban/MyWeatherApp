# MyWeatherApp
# My Weather App

A simple Flask-based weather app that fetches weather information using the OpenWeatherMap API.

## Features

- Search for a city to get the current weather
- Displays temperature in Celsius and Fahrenheit

## Installation

1. Clone the repository:

git clone https://github.com/edgyurban/MyWeatherApp.git



2. Change into the project directory:

cd my-weather-app



3. Create a virtual environment:

python -m venv venv



4. Activate the virtual environment:

- Windows:

venv\Scripts\activate



- Linux/macOS:

source venv/bin/activate



5. Install the required packages:

pip install -r requirements.txt



6. Create a `.env` file in the project root directory and add your OpenWeatherMap API key:

WEATHER_API_KEY=your_api_key_here



Replace `your_api_key_here` with your actual API key.

## Running the App

1. Activate the virtual environment if it's not already active (see step 4 in the Installation section).

2. Run the app:

python app.py



3. Open your web browser and go to `http://127.0.0.1:5000`.

## License

This project is licensed under the Creative Commons License.
