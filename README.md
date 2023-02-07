# Predict User Traffic for MercadoLibre

## Case study
With the aim of driving growth and revenue for [Mercado Libre](http://investor.mercadolibre.com/investor-relations), this 
tool imports both financial and user data to a Jupyter notebook, and generates visualisations to understand the time 
series data.

## Data sources
- Google hourly search trends: [google_hourly_search_trends.csv](Resources/google_hourly_search_trends.csv)
- MercadoLibre daily revenue: [mercado_daily_revenue.csv](Resources/mercado_daily_revenue.csv)
- MercadoLibre stock price: [mercado_stock_price.csv](Resources/mercado_stock_price.csv)

## Tasks to support the Analysis of the data
* Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
* Evaluation of how the company stock price correlates to its Google Search traffic.
* Prophet forecast model that can predict hourly user search traffic.
* Plot of a forecast for the company's future revenue.

## Technical Environment
This tool utilises the following technologies:
- **Pandas** DataFrame: [Documentation](https://pandas.pydata.org/docs/reference/frame.html)
- **hvplot** Bar chart, Line plot, Scatter:  [Documentation](https://hvplot.holoviz.org/getting_started/hvplot.html)
- **sklearn** Cluster, decomposition, preprocessing:  [Documentation](https://scikit-learn.org/stable/)

## Disclaimer
> Please be aware this is an Academic Case Study. The conclusions from this work should not be considered as financial 
> advice.
