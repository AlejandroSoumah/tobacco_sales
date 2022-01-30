# Prediction of Tobacco Sales in Spain

### 1.0 Explanation
This is an implementation of a time series <b>linear regression</b> for the quarterly prediction of tobacco sales in Spain. 

The data consists of:

  - <b>Monthly total sales of tobacco in Spain.</b>
  - <b>Monthly sales of tobacco per province.</b>
  - <b>Number of tourist overnight stays per month.</b>
  - <b>Unemployment rate per quarter.</b>


The data  consists of the total sales of tabacco in the whole in Spain, and also the total sales per province. Containing 50 provinces. The data also contains the total overnight stays, the unemployment rate and the price of tabacco. 

Using the prior monthly sales, number of tourist overnight stays and unemployent rate, we need to predict the total sale of tabacco per province and for total sales for Spain.

In order to do this two more linear regressions are implemented:

  - <b>Linear regression for the prediction of overnight tourist stays.</b>

  - <b>Linear regression for the prediction of unemployment rate per quarter.</b>

The data is then transformed to only contain quarterly information.

<b>The data consist of datapoints from 2013 to 2016, we test our model predicting for 2017  </b>

Beware data is written in spanish, the provinces also contain Spanish names, the code in itself and the graphs are all explained and written in English.
### 2.0 To execute
  - Using a notebook such as Jupyter Notebook, or Google Collab execute
### 3.0 Installation
  - 1 Install Python x3.6
  - 2 Install requirements from "requirements.txt"
  
  ````
    pip install requirements.txt
  ````
