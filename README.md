# Cinema Sales Analysis by Time Series
## Introduction
In this project we want to analyze the total sales of multiple cinemas using time series (Holt Winter). We also pretend to obtain relevant information like trend, seasonality, more important days.
## Objectives
Get the days that are more and less sales \\
Describe the seasonality of the dataset \\
Train the Holt Winters algorithm and make a prediction in a test set \\
## Data Source
It is a datase from Kaggle #https://www.kaggle.com/datasets/arashnic/cinema-ticket
## Methodology
In order to analize this dataset we have different approximations, the one we will use is to take the total sales of all the cinemas per day.

1. Data Preprocessing: Make a short clean of the data and create a dataset from the one we are using.

2. Exploratory Data Analysis (EDA): Explore the sales data visually to identify patterns, trends, and seasonal variations. This may involve plotting time series graphs, calculating summary statistics, and performing decomposition analysis.

3. Modeling: Apply time series modeling techniques, simple exponential smoothing and Holt Winters, we make a grid search to find the best period for the dataset.

4. Evaluation: Evaluate the performance of the time series models using such as mean squared error.

## Conclusion 
Using Holt Winters Exponential Smoothing we were capable of find the best seasonality for our dataset, and describe future sales in a test set.



