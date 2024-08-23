# Final Project: House Sales in King County, USA

This repository contains a Jupyter Notebook that demonstrates how to analyze and predict housing prices in King County, USA. The notebook performs the following tasks:

1. **Importing Data**
   - This module involves importing the dataset and preparing it for analysis. The dataset is loaded using pandas, and the relevant features are selected.
  
2. **Data Wrangling**
   - In this module, the dataset is cleaned and preprocessed. This includes handling missing values, converting data types, and performing any necessary data transformations.

3. **Exploratory Data Analysis**
   - This section involves exploring the dataset to understand the relationships between features and the target variable (price). Various visualizations and statistical analyses are performed.

4. **Model Development**
   - Here, we develop machine learning models to predict house prices. This includes:
   - Fitting a Linear Regression Model: Using the sqft_living feature to predict house prices.
   - Fitting a Ridge Regression Model: Applying a polynomial transformation of degree 2 to the features and fitting a Ridge regression model.

5. **Model Evaluation and Refinement**
   - In this module, the models are evaluated using R² scores. The performance of the models is assessed on both the training and test data.

## Running the Code
   - Clone the repository or download the notebook.
   - Ensure that you have the necessary libraries installed.
   - Open the Jupyter Notebook and run the cells to execute the analysis.

To execute this notebook, you need to have Python installed along with the following libraries:
   - `pandas`
   - `scikit-learn`
   - `numpy`
