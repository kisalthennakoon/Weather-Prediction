# Sri Lankan Weather Prediction

This project predicts the next day's maximum temperature in Celsius using today's weather data. The model is trained on Sri Lankan weather data and employs Ridge Regression. An interface using widgets is provided to input the necessary attributes and output the predicted temperature.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction
This project aims to predict the maximum temperature for the next day based on today's weather data. It specifically focuses on Sri Lankan weather conditions. The prediction model uses the following attributes:
- Today's maximum temperature
- Today's minimum temperature
- Today's precipitation
- Month's average maximum temperature

## Features
- **Weather Prediction**: Predicts the next day's maximum temperature in Celsius.
- **Interactive Interface**: A user-friendly interface built with widgets to input weather data and get predictions.

## Dataset
The model is trained on a dataset containing historical weather data for Sri Lanka. The dataset includes:
- Maximum temperature (Tmax)
- Minimum temperature (Tmin)
- Precipitation
- Month's average maximum temperature

## Model
The prediction model uses Ridge Regression to forecast the next day's maximum temperature. Ridge Regression is chosen for its ability to handle multicollinearity among the predictor variables.

## Installation
To run this project locally, follow these steps:
1. Clone the repository: `git clone https://github.com/yourusername/weather-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook to explore the project and make predictions.

## Usage
1. Open the Jupyter Notebook.
2. Run all cells to load the model and the widget interface.
3. Input today's maximum and minimum temperatures, precipitation, and the month's average maximum temperature.
4. Get the predicted maximum temperature for the next day.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
