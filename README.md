# Car Price Prediction using Machine Learning


## Project Overview

This project predicts the price of used cars using machine learning.
The model is trained on car listing data and uses features like
car name, company, year, kilometers driven, and fuel type.


## Dataset

The dataset is sourced from Quikr car listings and contains information
about used cars in the Indian market.

## Data Cleaning

The following steps were performed to clean the data:
- Removed invalid and non-numeric year values
- Cleaned price column by removing text and commas
- Processed mileage data and converted it to numeric format
- Removed rows with missing fuel type values
- Saved the cleaned dataset separately for reuse


## Model

In this project, a simple Linear Regression model is used to predict car prices.
Before training, categorical columns such as car name, company, and fuel type
are converted into numeric form using one-hot encoding.

## Results

The model achieved an R² score of approximately 0.9 on the test dataset,
indicating a good fit for the given data.

## How to Run the Project

1. Install the required libraries using:
   pip install -r requirements.txt

2. Open the Jupyter notebook inside the `notebooks` folder.

3. Run the cells step by step to clean the data, train the model,
   and test predictions.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
