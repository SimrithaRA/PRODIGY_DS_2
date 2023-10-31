# Exploratory Data Analysis (EDA) for Used Car Dataset

This repository contains code for performing Exploratory Data Analysis (EDA) on a used car dataset. The dataset was extracted from [Kaggle](https://www.kaggle.com/datasets/muhammadawaistayyab/used-cars-prices-in-uk/data).

## Introduction

The EDA process involves various steps to understand the dataset and extract insights. Here, we describe the key steps and provide the Python code used for analysis.

## Data Preprocessing

### Data Cleaning
We start by loading the dataset and addressing missing values:
- Replaced NaN values with 0 in the "Service history" and "Previous Owners" columns.
- Dropped columns with missing values: "Doors," "Seats," "Emission Class," and "Engine."

## Data Exploration

### Summary Statistics
- Calculated summary statistics for numerical columns, including "Price," "Mileage(miles)," "Registration_Year," and "Previous Owners."

### Data Visualization
- Created histograms to visualize the distribution of numerical data.
- Visualized the correlation between numerical variables using a heatmap.
- Generated a pair plot to explore pairwise relationships between variables.
- Created a box plot to analyze the relationship between "Fuel type" and "Price."

### Anomaly Detection
- Detected and visualized outliers in the "Price" column using Z-scores.

## Instructions for Running the Code

You can run the code provided in the Jupyter Notebook file named `EDA_Used_Cars.ipynb`. Make sure you have the necessary Python libraries installed to execute the code.

Feel free to use and adapt this code for your own data analysis projects.

## References

- [Kaggle Dataset](https://www.kaggle.com/datasets/muhammadawaistayyab/used-cars-prices-in-uk/data)

Happy analyzing!
