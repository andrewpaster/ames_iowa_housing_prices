# Predicting Ames Iowa Housing Prices

Predicting Housing Prices for Ames Iowa

This is a linear regression problem for predicting housing prices from Ames,
Iowa Data. This is part of a 
[Kaggle Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/leaderboard).

Thus far, the solution uses:
* Removing Outliers
* Feature engineering including mean encoding prices based on neighborhoods
* Imputation of Missing Data
* One Hot Encoding
* Three models ensembled into final prediction: Lasso Regression, SVM Regression, XGBoost Regressor

TODOS:
* Create more features especially mean encodings. Geographical data could be interesting for example.
* Try either ordinal encoding for some categorical variables
* Do a more thorough job of filling in missing data especially on the test set using KNeighbors or Regression
* Create a docker container on docker hub to share my environment with others
* Upload the model as a Flask app using Zappa
* Train the model with Amazon SageMaker

## Getting Started

These instructions will help you getting the code up and running.

### Prerequisites

To run this code, you will need Python and the ability to open Jupyter Notebooks.
You will also need to download the data sets from the 
[Kaggle Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/leaderboard).

The easiest way to run Jupyter notebooks and the necessarily libraries is by
installing [Anaconda](https://www.anaconda.com/)


### Installing

There is nothing to install other than what is listed under the pre-requisites.
From the terminal, make sure you are in the folder with the jupyter notebook.

Then type `jupyter notebook filename.ipynb`. You can then run the cells in the
Jupyter Notebook. Make sure the csv files and Jupyter Notebook are in the same
directory.

## Built With
* Python 
* Pandas 
* Scikit-learn
