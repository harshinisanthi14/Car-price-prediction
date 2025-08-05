# Car-price-prediction


A machine learning that predicts the resale price of a used car based on key features like year, mileage, engine capacity, fuel type, ownership history, brand, transmission, and more.

Dataset
The dataset used_car_price_dataset_extended.csv contains information about various used cars, including:
make_year
mileage_kmpl
engine_cc
fuel_type
owner_count
brand
transmission
color
service_history
accidents_reported
insurance_valid
price (target variable)


## Exploratory Data Analysis (EDA)
Checked data types and missing values.
Verified there are no missing values or outliers.
Visualized distributions and correlations of key features.

## Preprocessing
One-Hot Encoding for categorical variables (e.g., fuel type, brand).
Feature scaling using StandardScaler.
Aligned test input features during Gradio inference with training columns.

## Model Building
Model used: Linear Regression.
Evaluated using:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score (0.86 achieved)
