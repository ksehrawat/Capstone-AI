# Redfin House Price Prediction and Forecasting Project

## Project Overview

The main objective of the project was to explore house prices for the California, New York, and Texas states and analyze market trends for actionable insights. The project also aimed to forecast future house prices using advance machine learning models.

## DataSet

Initial DatSet was downloaded from the Redfin Website (https://www.redfin.com/news/data-center/) and then data was filetered furtner up to focus on the 3 states i.e. California, New York , and Texas. Initial DataSet (NewRedfinDataSet.csv) was stored in the Google Drive Folder so that it can used in Colab for further analysis.


## Data Exploration and Cleaning
### Initial Dataset:

* Rows: 66,577

* Columns: 50

### Key Cleaning Steps:

* Removed missing values and irrelevant columns.

* Handled outliers in median_sale_price using IQR.

* Converted period_begin to datetime format for time-based analysis.

### Final Dataset:

* Rows: 44,723

* Columns: 50
