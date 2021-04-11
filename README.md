## Time Series Forecasting Project - ( ARIMA )

In this Project, we are performing the Implementation of the ARIMA and Predicting using this Algorithm.

**Author : Ashish Kumar Patra**

**Date : 11st Apr 2021**

Sunspot Dataset
---------------------------

**Data Set Characteristics:**

 * This database contains 2 attributes.

               1: Date

               2: Monthly Mean Total Sunspot Number
               

## ARIMA ( Auto Regressive Integrated Moving Average )

       ARIMA is an acronym which stands for Auto Regressive Integrated Moving Average and is a way of modeling time-series data for
       forecasting and is specified by three order parameters (p,d,q):
       
       AR(p): Pattern of Growth / Decline in the Data is accounted for
       I (d): Rate of change of the Growth / Decline is accounted for
       MA (q): Noise between Time Points is accounted for
       
Steps Involved
-------------------------------

    1. Importing the Required libraries
    2. Data Loading and Basic Analysis 
    3. Data Preparing and Data Cleaning
    4. Data Visualization (Plotting Daily wise , Month wise and Year wise)
    5. Stationarity Testing
       - Dickey-Fuller Test
       - Kwiatkowski-Phillips-Schmidt-Shin Test
    6. Modeling and predicting
       - Rolling Mean
       - Weighted Moving Average
       - Exponential Weighted Moving Average
       - Exponential Smoothing Moving Average
       - Calculating RMSE
       - Seasonality , Trending and Noise Checking
       - Auto correlation Ploting
       - ARIMA



Install
-------------------------------
    Supported Python version
        -Python version used in this Project:3.5+

Libraries used
------------------------------
 * [Pandas](https://pandas.pydata.org/)
 * [Matplotlib](https://matplotlib.org/)
 * [Sklearn](https://scikit-learn.org/stable/)
 * [Numpy](https://numpy.org/)
 * [Seaborn](https://seaborn.pydata.org/)
 * [pmdarima](https://pypi.org/project/pmdarima/)


How to Run
------------------------------
    To run this Project you will need some Software, like Anaconda, which provides
    support for running .ipynb files (Jupyter Notebook).
