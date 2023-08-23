
# Car price prediction 

## Overview

This project aims to predict car prices using the various features of a car. A comprehensive study on the dataset is done and shown in the Jupyter notebook in this project. <br>
This project is to highlight EDA (Exploratory Data Analysis) and its importance.<br>
The dataset can be found in the 'Data' folder along with both training data and testing data, if you prefer data to be segregated.

## Notebook reference

Being a novice data scientist, I referred an amazing Jupyter notebook for this project. The link is down below:<br>
<a href="https://www.kaggle.com/code/goyalshalini93/car-price-prediction-linear-regression-rfe">Car Price Prediction(Linear Regression - RFE)</a><br>

## Model 

Linear regressor from the sklearn library was used as the model. 

Model uses RFE (Recursive Feature Elimination) to eliminate features with relatively less correlation with the dependent variable *price*. Moreover features with high VIF (Variance Inflation Factor) were eliminated to remove noise. 

## Environment Setup and Installation of required python libraries

If you want to follow this notebook and use all the features it includes, it is recommended to setup a virtual invironment and installing all the libraries by folling the below steps. <br>

\* ***The following steps assume that the project has already been pulled or atleast the requirements.txt*** \*

### Setting up the environment

- Installing the _virtualenv_ library :<br>
     **pip install virtualenv**

- Make a new project folder and after navigating to that folder using terminal, type the following command to initialize a python virtual environment : <br> **python\<version> -m venv \<virtual-environment-name>**

- Now activate the environment using the following command : <br>
    **source \<environment-name>/bin/activate**

- Once the environment is up and running, all the required libraries can be installed using the following command : <br>
    **pip install -r requirements.txt**

- If the environment is to be deactivated type:
    **deactivate**

All the above commands were run in ***Bash*** shell