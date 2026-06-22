# TRAIN DELAY PREDICTION MODEL
This repository contains a Jupyter Notebook designed to predict train delays using machine learning. The project environment can be launched directly via Google Colab
# Overview
The script loads historical train and weather data to train a predictive model. The primary objective is to estimate the Delay (minutes) based on environmental and operational factors using a RandomForestRegressor
## Dataset and Features
The model uses a dataset named `train_weather_delay_dataset.csv`. The dataset includes the following columns:
* `Date & Time`.
* `Train Type` (observed categories include Local, Freight, and Express).
* `Temperature (°C)`.
* `Rainfall (mm)`.
* `Wind speed (km/h)`.
* `Visibility (km)`.
* `Delay (minutes)` (Target variable).

## Tech Stack
The following Python libraries are installed and imported to handle data manipulation, machine learning, and visualization:
* pandas
* scikit-learn
* matplotlib
* seaborn

The model successfully outputs a predicted train delay of 26.53 minutes.
