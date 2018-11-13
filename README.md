# Predicting Ames Iowa Housing Prices

Predicting Housing Prices for Ames Iowa

This is a linear regression problem for predicting housing prices from Ames,
Iowa Data. This is part of a 
[Kaggle Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/leaderboard).

Thus far, the solution uses:
* Label Encoding for categorical features 
* Best guesses for missing values based on descriptions of the data or modes for categorical variables
* Lasso Regression

TODOS:
* Create more features especially mean encodings. Geographical data could be interesting for example.
* Try either ordinal encoding for some categorical variables and/or one-hot encoding
* Do a more thorough job of filling in missing data especially on the test set (or use XGBoost)
* Use lasso regression as a feature selector for other algorithms (Random Forest, Gradient Boosted Trees)
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
Python 
Pandas 
Scikit-learn
