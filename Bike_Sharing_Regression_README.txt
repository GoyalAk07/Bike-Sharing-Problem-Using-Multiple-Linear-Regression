
# Bike Sharing Demand Prediction Using Multiple Linear Regression

## Description

This project aims to predict the demand for bike rentals in a city based on various factors such as weather conditions, seasonality, and time of day. The project uses Multiple Linear Regression to model the relationship between the independent variables and the target variable, which is the count of bikes rented. The goal is to accurately forecast bike rental demand to assist in resource allocation and operational planning.

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository and contains the following features:

- Instant: Record index
- Date: Date (YYYY-MM-DD)
- Season: Season (1: Winter, 2: Spring, 3: Summer, 4: Fall)
- Year: Year (0: 2011, 1: 2012)
- Month: Month (1 to 12)
- Holiday: Whether the day is a holiday
- Weekday: Day of the week (0: Sunday, 1: Monday, ..., 6: Saturday)
- Workingday: Whether the day is neither a weekend nor a holiday
- Weather: Weather condition (1: Clear, 2: Mist, 3: Light Snow/Rain, 4: Heavy Rain/Snow)
- Temperature: Normalized temperature in Celsius
- Feels_like: Normalized feeling temperature in Celsius
- Humidity: Normalized humidity
- Windspeed: Normalized wind speed
- Casual: Number of non-registered user rentals
- Registered: Number of registered user rentals
- Count: Total number of bike rentals (target variable)

## Compilation

To run this project, you'll need the following Python libraries:

- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`
- `numpy`

Install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn scikit-learn statsmodels numpy
```

The project is implemented in a Jupyter Notebook and should be executed sequentially to ensure that all dependencies are correctly loaded.

## Format

The notebook is structured as follows:

1. Dataset Information: Overview and visualization of the dataset to understand the distribution of variables.
2. Exploratory Data Analysis: Analysis of the relationships between different variables and the target variable.
3. Feature Engineering: Creating new features and preparing the dataset for modeling.
4. Modeling: Implementing Multiple Linear Regression to predict bike rental demand, including model evaluation and interpretation of coefficients.
5. Conclusion: Summary of the model’s performance and insights derived from the analysis.

## Usage

To use this project:

1. Clone the repository or download the notebook and dataset.
2. Place the dataset in the same directory as the notebook.
3. Open the notebook in Jupyter and run the cells in order.

You can adjust the model parameters or experiment with different features to improve the prediction accuracy.

## Statistics

This project covers:

- Exploratory Data Analysis: Understanding the relationships between variables.
- Model Building: Implementing and interpreting Multiple Linear Regression.
- Model Evaluation: Assessing model performance using metrics such as R-squared and Mean Squared Error (MSE).
- Hypothesis Testing: Evaluating the significance of individual predictors.

## Conclusion

The project demonstrates the application of Multiple Linear Regression to predict bike rental demand, providing valuable insights into how various factors influence rental patterns.
