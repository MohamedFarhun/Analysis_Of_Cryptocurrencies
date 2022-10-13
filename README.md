# Analysis of cryptocurrencies
## This app gives us the analysis of various cryptocurrencies.
We have developed an app which predicts the future cryptocurrency values of btc-usd,eth-usd.Took the csv file of bitcoin and found the rolling mean,variance.Plotted the vanila decomposition graph for cryptos.
### Team Details:
#### Team Name: TEKKYZ
#### Team Leader: MOHAMED FARHUN M 
#### Members: NANDHAKUMAR S,DHIVAKAR S
#### Designation: Student at BANNARI AMMAN INSTITUTE OF TECHNOLOGY, SATHYAMANGALAM.
#### Contact: +919360593132
#### Mail: mohamedfarhun.it20@bitsathy.ac.in

## What we used......
• Daisi


• Streamlit UI


• pandas


• sklearn


• yfinance


#### We have done our project in the daisi platform (https://app.daisi.io/daisies/farhun/Analysis%20of%20cryptocurrencies/app) using Streamlit UI. We used yfinance-Yahoo finance(fetches live dataset of cryptos) from which we can have a statistical analysis of cryptos(graphically).
## Features
•Predicting Cryptocurrency graph variations from the start and end date


•predicts the future of cryptocurrency graph.


## Our daisi app

It is recommended to use this application on the daisi platform itself using the link https://app.daisi.io/daisies/farhun/Analysis%20of%20cryptocurrencies/app
However, you can still use your own editor using the below method:

###Python
See the docs for pyDaisi installation and authentication.

###Calling our app
import pydaisi as pyd
analysis_of_cryptocurrencies = pyd.Daisi("farhun/Analysis of cryptocurrencies")

###Documented endpoints
cryptocurrency
analysis_of_cryptocurrencies.cryptocurrency().value

analysis_of_cryptocurrency
analysis_of_cryptocurrencies.analysis_of_cryptocurrency().value

app
analysis_of_cryptocurrencies.app().value


bitcoin
analysis_of_cryptocurrencies.bitcoin().value


st_ui
analysis_of_cryptocurrencies.st_ui().value

###Undocumented endpoints
##Consider adding docstrings for these functions in your code.

test_stationarity
analysis_of_cryptocurrencies.test_stationarity(timeseries).value

###R
library(rdaisi)
configure_daisi(python_path="/usr/local/bin/python3")
analysis_of_cryptocurrencies <- Daisi("farhun/Analysis of cryptocurrencies")

###Endpoints
cryptocurrency
analysis_of_cryptocurrencies$cryptocurrency()$value()

analysis_of_cryptocurrencies$analysis_of_cryptocurrency()$value()

app
analysis_of_cryptocurrencies$app()$value()

bitcoin
analysis_of_cryptocurrencies$bitcoin()$value()

st_ui
analysis_of_cryptocurrencies$st_ui()$value()

test_stationarity
analysis_of_cryptocurrencies$test_stationarity(timeseries)$value()

