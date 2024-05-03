# Introduction to AI

## Introduction
This repository contains various notebooks covering different modules of the Introduction to Artificial Intelligence course at [GOMYCODE](https://gomycode.com/dz/courses/introduction-to-artificial-intelligence/).

## Project Structure
- `data/`: Contains the dataset files used in these projects.
- `data_visualization.ipynb`: Jupyter Notebook containing the Python code for data preprocessing and visualization.
- `regression_models.ipynb`: this Jupyter Notebook focuses on building and comparing regression models.
- `logistic_regression.ipynb`: this Jupyter Notebook focuses on implementing logistic regression.
- `KNN_from_scratch.ipynb`: this Jupyter Notebook demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm from scratch.
- `README.md`: This documentation file providing an overview of the project.

## Data Source
- `state_weather_aqi_data_mf2.csv` : this dataset includes state weather and air quality index (AQI) data. It was obtained from [kaggle](https://www.kaggle.com/datasets/ishanmujumdar/aqi-data).
- `kc_house_data.csv` : this dataset includes various features related to houses, and the target variable is the house price. It was obtained from [kaggle](https://www.kaggle.com/datasets/shivachandel/kc-house-data).
- `titanic-passengers.csv` : The Titanic dataset contains information about passengers, including whether they survived or not.
- `iris.data` The dataset used is the Iris classification dataset, consisting of 150 observations of iris flowers from three different species.

## Modules Included

### 1. Data Visualization
- **File:** [data_visualization.ipynb](data_visualization.ipynb)
- **Description:** Comprehensive data visualization notebook showcasing:
    - Utilization of Plotly for dynamic visualizations.
    - Area and histogram charts for effective data representation.
    - Seaborn's powerful capabilities in creating scatter plots and bar plots.


### 2. Logistic Regression
- **File:** [logistic_regression.ipynb](logistic_regression.ipynb)
- **Description:** In-depth exploration of logistic regression with practical implementations:
    - Logistic regression applied with one dimension and multiple dimensions using selected features.
    - Use a confusion matrix to validate the model.
    - Researched and explained ROC (Receiver Operating Characteristic) and AUC (Area Under the Curve),implemented them for both one-dimensional and multiple-dimensional logistic regression models, providing visual representations of model performance.


### 3. Regression Models
- **File:** [regression_models.ipynb](regression_models.ipynb)
- **Description:** Master the principles of regression in supervised machine learning.
    - Implement linear regression, multi-linear regression, and polynomial regression.
    - Explore methods to handle outliers, understand model performance metrics, and make informed choices when selecting regression algorithms


### 4. K-Nearest Neighbors (KNN) from Scratch
- **File:** [KNN_from_scratch.ipynb](KNN_from_scratch.ipynb)
- **Description:** Demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm from scratch.
    - Implemented a function to get the k most similar neighbors.
    - Developed a function to determine the majority voted response from the neighbors (essentially predicting the class of the test instance)
    - Evaluated the accuracy of the KNN algorithm by calculating the ratio of total correct predictions out of all predictions made (classification accuracy).
 