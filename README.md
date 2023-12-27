# Sales Forecasting for a Bakery Branch via Linear Regression (R)

This project belongs to a [group project](https://github.com/annapuu/gruppe3) which is part of the course "Introduction to Data Science & Machine Learning" by opencampus.sh. The code was written by me with the help of ChatGPT. It shows a linear regression, utilizing historical sales data spanning from July 1, 2013 to July 30, 2018 to predict the sales of a bakery branch for the following year. The aim is to predict future sales for six specific product categories: Bread, Rolls, Croissants, Confectionery, Cakes and Seasonal Bread.

For this course, the sales and weather data were provided by [meteolytix](https://meteolytix.de/).

## Files
- [data.R](https://github.com/annapuu/linear-regression-bakery-sales/blob/main/data.R): data preparation, which means importing, joining and creating the needed data and filling certain missing values
- [data.csv](https://github.com/annapuu/linear-regression-bakery-sales/blob/main/data.csv): the prepared dataset
- [baseline_model.nb.html](https://htmlpreview.github.io/?https://raw.githubusercontent.com/annapuu/linear-regression-bakery-sales/main/baseline_model.nb.html): in this notebook, the data is sorted and divided into training, validation and test data before searching for the best linear model
- [model_7.nb.html](https://htmlpreview.github.io/?https://raw.githubusercontent.com/annapuu/linear-regression-bakery-sales/main/model_7.nb.html): preparation of test data, prediction for validation data and assessing its performance as well as prediction for the test data
- [gruppe3_submission.csv](https://github.com/annapuu/linear-regression-bakery-sales/blob/main/gruppe3_submission.csv): predicted data

## Libraries
- readr
- dplyr
- lubridate
