# Weather Data Fetch and Visualization

This repository contains a Python application that fetches real-time weather data from the OpenWeatherMap API, generates sample data, combines both datasets, performs data analysis, and visualizes various weather metrics.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Code Overview](#code-overview)
- [Usage](#usage)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before running the application, ensure you have the following prerequisites installed:

- Python 3.7 or higher
- `pip` (Python package installer)

You can create a virtual environment to manage dependencies. Install the necessary libraries using:

```bash
pip install requests pandas matplotlib seaborn
```
# Setup
## Clone the Repository:
```
git clone https://github.com/CodeSage4D/WheaterFetch.git
cd WheaterFetch
```
## Create and Activate a Virtual Environment:
```
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
## Install Dependencies:
```
pip install requests pandas matplotlib seaborn
```
## Run Jupyter Notebook (Optional):
If you prefer using Jupyter Notebook for running the code:
```
pip install jupyter
jupyter notebook
```
Open the notebook file in your browser and run the cells.

# Code Overview
## Fetching Real-Time Weather Data
The fetch_real_time_weather_data function retrieves current weather data from the OpenWeatherMap API.

## Key Points:
Uses the OpenWeatherMap API to fetch data.
Extracts and stores temperature, humidity, wind speed, air pressure, and cloud coverage.

## Generating Sample Data
The generate_sample_data function creates simulated weather data for testing purposes.

## Key Points:
Generates random values for temperature, humidity, and wind speed.
Provides a range of timestamps to simulate past weather conditions.

# Combining Data
The combine_data function merges real-time and sample weather data into a single DataFrame.

## Key Points:
Concatenates real-time data with generated sample data.
Resets the DataFrame index to ensure continuity.

# Data Visualization
The plot_combined_weather_data function visualizes the combined weather data using various plots.

## Key Points:
Plots trends for temperature, humidity, wind speed, air pressure, and cloud coverage.
Utilizes matplotlib and seaborn for enhanced visualization.

# Visualization
The application generates several plots to visualize weather data:
1. Temperature Trend: Shows changes in temperature over time.
2. Humidity Trend: Displays variations in humidity levels.
3. Wind Speed Trend: Illustrates wind speed changes.
4. Air Pressure Trend: Depicts air pressure fluctuations.
5. Cloud Coverage Trend: Represents cloud coverage as a proxy for precipitation.
6. Each plot is configured with labels, grid lines, and rotated x-ticks for better readability.

# Contributing
Contributions are welcome! Please open an issue or submit a pull request with your improvements.
