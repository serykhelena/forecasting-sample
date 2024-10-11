# Forcasting Sample Project


[![PythonSupported](https://img.shields.io/badge/python-3.10-brightgreen.svg)](https://python3statement.org/#sections50-why)

- [Overview](#overview)
- [Project Contents](#project-contents)
- [Sample Data](#sample-data)
- [Requirements](#requirements)
- [How to Use](#how-to-use)
- [Results](#results)
- [Contributing](#contributing)




This project is an educational tool aimed at helping users understand and implement time series forecasting using both classical and machine learning models.


## Overview

This is project for study purpuse only. This proejcts demonstrates a time series forecasting task using the ETNA Holt-Winters model and autoregression models like Linear Regression and LightGBM (LGBM). The project is structured entirely in Jupyter notebooks and includes a complete end-to-end pipeline, from data analysis and preprocessing to model training, forecasting, and evaluation.

## Project Contents

* [Data Analysis Notebook](./notebooks/00-data-analysis.ipynb): Initial exploratory data analysis (EDA) 
* [Data Preprocessing Notebook](./notebooks/01-data-preprocessing.ipynb): preprocessing to prepare the dataset for forecasting
* [Holt Winters Model Training Notebook](./notebooks/02-statistic-models.ipynb): Implementation of Holt-Winters model (using ETNA) 
* [Autoregression Model Training Notebook](./notebooks/03-regression-models.ipynb): Implementation of autoregressive approaches 
* [Model Evaluation Notebook](./notebooks/04-evaluation.ipynb): Comprehensive evaluation of model performance, including error metrics and visualizations to compare results.

## Sample Data

The project includes sample data to demonstrate how the models work on real-world time series data. The data contains time-stamped values that are suitable for forecasting tasks.
For simplicity only one timeserie has been used. [Source Data](https://www.kaggle.com/datasets/theforcecoder/wind-power-forecasting)


## Requirements
* Python version: 3.10
* Libraries: [requirements](./requirements.txt)


## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/serykhelena/forecasting-sample.git
    ````

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ``` 

## Results

The project explores various models for time series forecasting and compares their performance using standard evaluation metrics (e.g., MAPE, MAE, RMSE). The notebooks provide a detailed breakdown of each step, from data analysis to forecasting, with clear visualizations to assess model accuracy.

## Contributing
Feel free to fork this repository and make improvements or suggest new features! Contributions are always welcome.
