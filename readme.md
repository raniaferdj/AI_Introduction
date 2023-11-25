# Data Visualization Project

## Introduction
This repository contains a Jupyter Notebook for a data visualization project completed as part of the Introduction to Artificial Intelligence course at [GOMYCODE](https://gomycode.com/dz/courses/introduction-to-artificial-intelligence/). The project focuses on the preprocessing and visualization phases using Python, with an emphasis on data processing and visualization libraries such as Matplotlib, Seaborn, and Pandas. The dataset used in this project includes state weather and air quality index (AQI) data.

## Data Source
The dataset used in this project, `state_weather_aqi_data_mf2.csv`, was obtained from [kaggle](https://www.kaggle.com/datasets/ishanmujumdar/aqi-data).

## Project Structure
- `data/`: Contains the dataset file (`state_weather_aqi_data_mf2.csv`).
- `data_visualization.ipynb`: Jupyter Notebook containing the Python code for data preprocessing and visualization.
- `README.md`: This documentation file providing an overview of the project.

## Project Highlights
### 1. Preprocessing Phase
- Data loading and initial exploration using Pandas.
- Handling missing values and dropping unnecessary columns.
- Label encoding for categorical variables.

### 2. Visualization Phase
- Histogram of AQI distribution.
- Distribution of all variables using a facet grid.
- Scatterplots to visualize the correlation between numerical variables and the target (AQI).
- Bar plot to show the mean AQI values for each city.

### 3. Custom Function - `plot_correlation_map`
- A custom function that generates a color-coded heatmap illustrating the correlation between all pairs of variables in the dataset.
- Useful for identifying patterns and relationships between different variables.

## How to Use
1. Ensure you have Python and Jupyter Notebook installed.
2. Install the required libraries: Pandas, Matplotlib, Seaborn, and Scikit-learn.
3. Open the Jupyter Notebook (`data_visualization.ipynb`) and run each cell sequentially.

## Analysis
The provided custom function, `plot_correlation_map`, generates a heatmap that visually represents the correlation between different variables in the dataset. Correlation coefficients are indicated by colors, helping to identify patterns and relationships. This visualization is valuable for feature selection in machine learning models.

