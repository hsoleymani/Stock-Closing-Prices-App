# Stock Closing Price application (author: Hamid Soleymani 2021)
# https://stock-close-price.herokuapp.com/

This is an Streamlit app on Heroku that accepts a stock ticker input from the user and plots closing price data for one month (one of your choosing or perhaps one chosen by the user). the data source is the Alpha Vantage API, which provides data for free (a free API key). I used Python's Requests library along with simplejson to access the Alpha Vantage API. I analyze the data using pandas and plot using Plotly.
