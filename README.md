# Sales Forecasting for a Bakery Branch via Linear Regression (R)

This project belongs to a [group project](https://github.com/annapuu/gruppe3) which is part of the course "Introduction to Data Science & Machine Learning" by opencampus.sh. The code was written by me. It shows a linear regression, utilizing historical sales data spanning from July 1, 2013 to July 30, 2018 to predict the sales of a bakery branch for the following year. The aim is to predict future sales for six specific product categories: Bread, Rolls, Croissants, Confectionery, Cakes and Seasonal Bread.

For this course, the sales and weather data were provided by [meteolytix](https://meteolytix.de/).

## Files
- data.R: data preparation, which means importing, joining and creating the needed data and filling certain missing values
- baseline_model.Rmd: in this notebook, the data is sorted and divided into training, validation and test data before searching for the best linear model
- model_7.Rmd: preparation of test data, prediction for validation data and assessing its performance as well as prediction for the test data

## Libraries
- readr
- dplyr
- lubridate
