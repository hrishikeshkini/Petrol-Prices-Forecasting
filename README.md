# Petrol Prices Forecasting

## Table of Content
  * [Problem Statement](#problem-statement)
  * [Approach](#approach)
  * [Technologies Used](#technologies-used)
  * [Installation](#installation)
  * [Bugs & Logs](#bugs--logs)
  * [Contributors](#contributors)

![Screenshot](download.jpg)


## Problem Statement
Petrol Prices are going up continously these days and it has become very hard to predict what will be the price range in the next few months or even days. 

In this project we will try to forecast the different petrol prices for the upcoming dates given to us.

We will use LSTM and ARIMA forecasting models to predict the prices then we will see how we can implement the same using Auto Keras, which is an Auto ML Library.

![Autokeras](autokeras.png)

An AutoML system based on Keras. It is developed by DATA Lab at Texas A&M University

## Approach
Data Exploration : I started exploring dataset using pandas,numpy,matplotlib and seaborn.

Data visualization : Ploted graphs to get insights about dependend and independed variables.

Feature Engineering : Removed missing values and created new features as per insights.

Model Building & Testing : Tried many machine learning algorithms and checked the base accuracy to find the best fit.

Model Building using Auto SKLearn(Auto ML)

## Technologies Used
 
   1. Python 
   2. Sklearn
   3. Lstm
   4. RNN
   5. Autokeras
   6. Pandas, Numpy 

## Dataset
[Download here](https://github.com/hrishikeshkini/Petrol-Prices-Forecasting/blob/main/train_data.csv)

## Installation
Click here to install [python](https://www.python.org/downloads/). To install the required packages and libraries, run this pip command in the project directory after cloning the repository:
```bash
git clone https://github.com/hrishikeshkini/Petrol-Prices-Forecasting.git
pip install -r requirements.txt
```
If pip is not already installed, Follow this [link](https://pip.pypa.io/en/stable/installation/)

## Bugs & Logs

1. If you find a bug, kindly open an issue and it will be addressed as early as possible. [Open](https://github.com/hrishikeshkini/Petrol-Prices-Forecasting/issues)
2. Under localhost, logging is performed for all the actions and its stored onto logs.txt file
3. When the app is deployed on heroku, logs can be viewed on  heroku dashboard or CLI.

## Contributors
  [Hrishikesh Kini](https://github.com/hrishikeshkini)

