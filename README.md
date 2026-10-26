# Air Quality Prediction Using a Neural Network

## Overview

This project investigates whether a feedforward neural network (Multilayer Perceptron) can estimate carbon monoxide (CO) concentration using air-quality sensor readings and meteorological variables.

The project compares the neural network with traditional machine learning models to evaluate prediction performance.

## Research Question

How effectively can a neural network estimate CO concentration from environmental sensor measurements, and does including meteorological variables improve prediction performance?

## Dataset

- **Source:** [UCI Air Quality Dataset](https://archive.ics.uci.edu/dataset/360/air+quality)
- **Observations:** Hourly air-quality measurements collected in an Italian city.
- **Target variable:** `CO(GT)`
- **Input features:** Sensor responses, temperature, humidity, and time-related features.

The dataset is not representative of Sri Lankan air quality. The project evaluates a prediction methodology using historical data from Italy.

## Methodology

1. Data cleaning and exploratory data analysis.
2. Missing-value handling and feature preparation.
3. Chronological training, validation, and test split.
4. Training baseline models.
5. Building a feedforward neural network.
6. Comparing models using MAE, RMSE, and R².
7. Analysing prediction errors and model limitations.

## Models

- Median baseline
- Linear Regression
- Random Forest Regressor
- Multilayer Perceptron (MLP) Regressor

## Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Status

In progress. Model performance and conclusions will be added after the experiments have been completed.

## Limitations

This project uses historical data from Italy. Its results should not be interpreted as a validated air-pollution monitoring system for Sri Lanka.

## Reproducibility

Dataset instructions, dependencies, preprocessing steps, and experiments will be documented in this repository.

## Author

Data Science undergraduate | Sri Lanka