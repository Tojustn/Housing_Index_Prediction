# Housing Index Prediction using Lasso Regression

This project implements a predictive model using **Lasso Regression** to forecast future housing index values. The data is based on the **Federal Housing Finance Agency (FHFA)** index values and is used to predict trends in housing prices for the upcoming years.

## Project Overview

The goal of this project is to utilize a **Lasso linear regression model** to predict future housing index values from 2025 to 2030. The model is trained on historical data from the FHFA and produces accurate predictions with a high R² score and low Mean Squared Error (MSE).

### Key Features:
- **Lasso Regression**: Used to predict future housing index values.
- **Scikit-learn**: For building and training the predictive model.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization of the housing index trends.
- **CSV Integration**: Using historical data from the **Federal Housing Finance Agency (FHFA)**.

## Dataset

The dataset was sourced from the [Federal Housing Finance Agency (FHFA)](https://www.fhfa.gov/DataTools/Downloads/Pages/House-Price-Index-Datasets.aspx) and includes housing index values from 1991 to 2024.


## Model

The predictive model is built using **Lasso Regression**, a linear regression technique that performs both feature selection and regularization. The model is trained on the historical housing index data, and its accuracy was tested on a separate validation set.

### Model Results:

- **R² Score**: 75%
- **Mean Squared Error (MSE)**: ~1500
- **Predicted Housing Index**: 
  - 2025: 300
  - 2030: 322
