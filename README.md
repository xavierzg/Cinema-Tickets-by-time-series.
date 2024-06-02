# Cinema Sales Analysis by Time Series
## Introduction
In this project we want to analyze the total sales of multiple cinemas using multiple algorithms and determine which one is the best in this case.
## Goals
Clean the dataset to be compatible with the algorithms <br>
Describe the algorithms performance based on corresponding error parameters and computation time.
## Data Source
It is a dataset from Kaggle #https://www.kaggle.com/datasets/arashnic/cinema-ticket
## This project's repo includes the following files:
The procces to clean the dataset and some descriptive algorithms (1_Series.ipynb) <br>
Implementation of multiple algorithms (2_ARIMA.ipynb, 3_VARIMA.ipynb, 4_ML_Algorithms.ipynb) <br>
The original data (cinemaTicket_Ref.csv) <br>
The clean data (clean_data.csv)
## This project includes the following steps:
1. Decision of how to approach to the dataset. <br>
2. Analysis of important dates, days, stationality and outliers. <br>
3. Analysis with some algorithms. <br>
4. Use of distinct error measurement. <br>
5. Implementation of algorithms (Holt Winters, ARIMA, VARIMA, Linear Regression).

## Conclusion
Holt Winters: $R^2 = -0.0483$, Time = 2.3s. <br>
ARIMA: t statistic = 0.210, p-value = 1.434e-08, Time = 18 min. <br>
VARIMA: $R^2_1 = -0.623, R^2_2 = = -0.407$, Time = 9 hours. <br>
Linear Regression (1-step): $R^2 = 0.595$, Time = 0.3s
Linear Regression (multi output): $R^2 = 0.432$, Time = 1.8s


