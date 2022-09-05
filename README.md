# Forecasting-for-MercadoLibre
With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. As a growth analyst at MercadoLibre, I have been tasked with analyzing the company's financial and user data in clever ways to make the company grow. Using Prophet, I am attempting to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

## Technologies
Resources include 3 csv files:
"google_hourly_search_trends.csv"
"mercado_stock_price.csv"
"mercado_daily_revenue.csv"

Tools

!("screenrec/google_colab.gif")

Libraries and dependencies:
- import pandas as pd
- import holoviews as hv
- from prophet import Prophet
- import hvplot.pandas
- import datetime as dt
- %matplotlib inline

## Installation Guide
Installation requirements for this project included Python and Panda Libraries, Pystan, FbProphet, HvPlot and Holoviews

- !pip install pystan
- !pip install fbprophet
- !pip install hvplot
- !pip install holoviews

## Results
Although there was no significant positive correlations in search trends to stocks the forecasting model does indicate that the company is on a growth trejectory.
