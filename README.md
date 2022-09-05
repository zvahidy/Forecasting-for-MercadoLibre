# Forecasting-for-MercadoLibre
With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. As a growth analyst at MercadoLibre, I have been tasked with analyzing the company's financial and user data in clever ways to make the company grow. Using Prophet, I am attempting to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

## Technologies
Resources included 3 csv files:
- "google_hourly_search_trends.csv" 

https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/Resources/google_hourly_search_trends.csv
- "mercado_stock_price.csv"  

https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/Resources/mercado_stock_price.csv
- "mercado_daily_revenue.csv" 

https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/Resources/mercado_daily_revenue.csv

Tools
Google Colab
![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/google_colab.gif)

Libraries and dependencies:
- import pandas as pd
- import holoviews as hv
- from prophet import Prophet
- import hvplot.pandas
- import datetime as dt
- %matplotlib inline

![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/library_and_dependencies.png)

## Installation Guide
Installation requirements for this project included Python and Panda Libraries, Pystan, FbProphet, HvPlot and Holoviews

- !pip install pystan
- !pip install fbprophet
- !pip install hvplot
- !pip install holoviews

![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/Install.png)

## Results
Convert Data to Datetine
![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/to_datetime.png)
Review hourly trend
![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/hourly_trend.png)
Compare Closing stock data to search trends
![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/close_search_trends.png)
localize concentration of search traffic using heat mapping
![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/heat_map.png)
Determine if correlation has statistical significance
![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/correlation.png)
Forecast company growth using modeling
![](https://github.com/zvahidy/Forecasting-for-MercadoLibre/blob/main/screenrec/plot_forecast.png)


Although there was no significant positive correlations in search trends to stocks the forecasting model does indicate that the company is on a growth trejectory.

## Contributors

#### Contact
zehra.vahidy@gmail.com
LinkedIn https://www.linkedin.com/in/zehra-vahidy-6025b820

---

## License

Unlicesened

## Appendix
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings
https://jupyterlab.readthedocs.io/en/stable/
