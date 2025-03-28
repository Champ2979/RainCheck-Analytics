# 🌧️ RainCheck Analytics - A Weather Prediction Model

## Overview
A Gaussian Naive Bayes machine learning model for weather prediction in Seattle ```(you can use the same data points from any city Data and follow the steps to predict the weather)```, using historical weather data and OpenWeatherMap API integration for future forecasts. Predicts weather conditions (rain, sun, drizzle, etc.) based on precipitation, temperature, and wind features.

## Features
- Data preprocessing and exploration
- Gaussian Naive Bayes classification
- Model persistence with Joblib
- 5-day weather forecast integration with OpenWeatherMap API
- Prediction visualization and CSV export
- API key security using environment variables

## Installation 
1. Clone repository:
```bash
git clone https://github.com/Champ2979/RainCheck-Analytics
cd RainCheck-Analytics

```
## Install Dependencies
```bash
pip install -r requirements.txt
```
## Create .env file:
```bash
OPENWEATHER_API_KEY="your_api_key_here"
```

## Follow notebook steps to:

- Train model on historical data
- Save trained model
- Get 5-day forecasts
- Make predictions using the saved model

## API Key Setup
- Get free API key from OpenWeatherMap

- Add to .env file:
```bash
OPENWEATHER_API_KEY="your_actual_key_here"
```
## Model Performance
- Training Accuracy: 85.42%
- Testing Accuracy: 84.74%

### Confusion Matrix visualization included

## Dependencies
- Python 3.8+

- scikit-learn

- pandas

- matplotlib

- requests

- python-dotenv

- joblib

## License
- MIT License

## Acknowledgements
- Dataset: Seattle Weather Dataset
- Weather API: OpenWeatherMap

