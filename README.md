# 🌦️ Weather Data Analysis using Pandas

## 📌 Project Overview

This project performs **exploratory data analysis (EDA)** on a weather dataset using Python and Pandas.
The dataset contains hourly weather information such as temperature, humidity, wind speed, pressure, and weather conditions.

The notebook demonstrates how to analyze and extract insights using various Pandas operations.

## 📂 Dataset Description

The dataset includes the following features:

* Temperature
* Dew Point Temperature
* Relative Humidity
* Wind Speed
* Visibility
* Pressure
* Weather Conditions

It is a **time-series dataset** with hourly weather records.

## 🛠️ Technologies Used

* Python 🐍
* Pandas 📊
* Jupyter Notebook

## 🔍 Key Concepts Covered

### 📊 Data Exploration

* Viewing data using `.head()`
* Understanding dataset shape using `.shape`
* Checking column names and data types
* Using `.info()` for dataset summary

### 📈 Data Analysis Techniques

* Finding unique values using `.unique()` and `.nunique()`
* Counting values using `.value_counts()`
* Handling missing values using `.isnull()` and `.notnull()`
* Renaming columns

### 📉 Statistical Analysis

* Mean calculation (`.mean()`)
* Standard deviation (`.std()`)
* Variance (`.var()`)

## 📊 Sample Operations Used

* Filtering:
  data[data['Wind Speed_km/h'] == 4]
* Grouping:
  data.groupby('Weather Condition').mean()
* String filtering:
  data[data['Weather Condition'].str.contains('Snow')]
 
## 📁 Project Structure

├── Weather Analysis.ipynb
├── Weather Data.csv
├── README.md

## 📌 Key Insights

* Weather conditions like *Clear*, *Snow*, etc., can be analyzed effectively
* Wind speed and visibility patterns can be filtered and studied
* Grouping helps understand average conditions for each weather type
* Pandas provides powerful tools for quick data analysis

## 🎯 Conclusion

This project showcases how **Pandas can be used for real-world data analysis** by applying filtering, grouping, and statistical techniques on a weather dataset.

