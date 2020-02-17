# Overview

**Goal** 
The goal of this project is to find out if a global warming trend exists and if so,
to fit the trend using Central England temperature data from 1659-2019. 

**Method** 
First I averaged the seasonal temperature readings to create an annual time series of temperature data.
Then I detrended the data using 3 forms of regression: linear, quadratic, and cubic.

**Files** 
* global_warming.Rmd - R Markdown file containing R code with 
* global_warming.pdf - pdf output of R Markdown 
* England_temp_timeseries.txt - txt file containing Central England mean temperatures for every season from 1659-2019.

**Limitations**
For security reasons, the data only includes Census track centroid pickup and 
dropoff coordinates. This means we are only able to get at best within about
an 89,000 square foot radius of the actual pickup and dropoff locations so our 
intersection coordinates are not exactly accurate. Also, the timestamps are rounded
to the nearest 15 minutes.

# Features
* R 
* Time Series trend fitting
* Regression
* Detrending

# Technologies
* R
* atsa - Time Series package

# Authors
* Tyson Miller
