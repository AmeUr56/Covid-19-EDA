# Project Idea: 
Exploratory Data Analysis on COVID-19 Dataset

## Overview  
This project explores and analyzes the **COVID-19 dataset** using exploratory data analysis (EDA) techniques. The goal is to understand trends, patterns, and insights from the data.  

## Tools and Libraries  
- **Python**  
- **Pandas** for data manipulation  
- **NumPy** for numerical operations  
- **Matplotlib** and **Seaborn** for visualizations  

# The Dataset: 
COVID-19 Pandemic by Our World in Data. 

## **Link**: https://docs.owid.io/projects/etl/api/covid/

## Features(Columns) Description
- **country**: The name of the country.
- **date**: The date of the recorded data.
- **total_cases**: Cumulative number of confirmed COVID-19 cases.
- **new_cases**: Number of new cases reported on a given day.
- **new_cases_smoothed**: Seven-day moving average of new cases to reduce daily fluctuations.
- **total_cases_per_million**: Total cases adjusted per million people.
- **new_cases_per_million**: New cases adjusted per million people.
- **new_cases_smoothed_per_million**: Smoothed new cases adjusted per million people.
- **total_deaths**: Cumulative number of confirmed COVID-19 deaths.
- **new_deaths**: Number of new deaths reported on a given day.
- **population**: Total population of the country.
- **population_density**: Number of people per square kilometer.
- **median_age**: Median age of the population.
- **life_expectancy**: Average life expectancy in the country.
- **gdp_per_capita**: Gross Domestic Product per capita.
- **extreme_poverty**: Percentage of the population living in extreme poverty.
- **diabetes_prevalence**: Percentage of the population with diabetes.
- **handwashing_facilities**: Access to basic handwashing facilities (% of population).
- **hospital_beds_per_thousand**: Number of hospital beds available per thousand people.
- **human_development_index**: A composite index measuring overall human development (health, education, and income).

# API
I created small api for sharing data between notebooks.

## Endpoints:
- **/raw_data**: to transfer raw data between notebooks.
    - **POST**: to upload the raw data to the api.
    - **GET**: to fetch it from the api.

- **/processed_data**: to transfer processed data between notebooks.
    - **POST**: to upload the processed data to the api.
    - **GET**: to fetch it from the api.
    
# EDA Workflow
## 1. Data Collection

## 2. Data Cleaning & Processing
- 2.1 Handling Missing Values
- 2.2 Handling Duplicates
- 2.3 Date Handling
- 2.4 Feature Engineering

## 3. Data Exploration & Visualization
- 3.1 Univariate Analysis
- 3.2 Bivariate Analysis 
- 3.3 Geospatial Visualization
- 3.4 Time Series Analysis
- 3.5 Multivariate Analysis

## 4. Statistical Analysis
- 4.1 Descriptive Statistics
- 4.2 Trend Analysis
- 4.3 Outlier Detection
- 4.4 Hypothesis Testing

## 5. Insights & Conclusion

# How to Run  

## 1. Clone this repository:  
```
git clone https://github.com/AmeUr56/Covid-19-EDA
```

## 2. Install the required libraries:
```
pip install -r requirements.txt  
```
## 3. Run the API
```
cd API
flask run
```
## 4. Run the Jupyter notebooks or Python scripts to explore the data.

# Contribution
Feel free to contribute by submitting pull requests or reporting issues!

# License
This web app is licensed under the [MIT License](./LICENSE.md).  
Copyright (c) 2024 [Ameur].