# Car Price Prediction

This project is about predicting the price of used cars based on various features such as the car's brand, model, year of manufacture, mileage, fuel type, and other relevant factors. The aim of this project is to build a machine learning model that can accurately predict the price of a used car based on these features.

## Dataset

The dataset used for this project is the quikr car dataset, which can be found on Kaggle. The dataset contains information about used cars listed on the CarDekho website. It has 892 rows and 6 columns, including the target variable, which is the selling price of the car.

## Preprocessing

Before building the machine learning model, the dataset was preprocessed to handle missing values, categorical variables, and outliers. The following steps were taken:

- Missing values were handled by either dropping the rows or imputing the missing values with the mean or mode of the respective column.
- Categorical variables were encoded using one-hot encoding.
- Outliers were detected and removed using the IQR method.

## Model Building

The machine learning model used for this project is the Linear Regression with pipeline. The model was trained on 80% of the dataset and tested on the remaining 20%. The model achieved an R-squared score of 0.8134, indicating that it can explain 81% of the variance in the target variable.
