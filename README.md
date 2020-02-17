# Overview

**Goal** 
The goal of this project is to find out if a global warming trend exists and if so,
to fit the trend using Central England temperature data from 1659-2019. 

**Method** 
First I averaged the seasonal temperature readings to create an annual time series of temperature data.
Then I detrended the data using 3 forms of regression: linear, quadratic, and cubic. I then analyzed each model using data visualization and ANOVA tables to determine that the cubic model fit the data the best. Finally, I detrended the data and used
MannKendall test to test for linear trends in each of the seasonal datasets.

**Files** 
* global_warming.Rmd - R Markdown file containing R code with 
* global_warming.pdf - pdf output of R Markdown 
* England_temp_timeseries.txt - txt file containing Central England mean temperatures for every season from 1659-2019.

**Limitations**
The data we used is only for central england temperatures, it may not be an indication of 
global warming trends as a whole. 

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
