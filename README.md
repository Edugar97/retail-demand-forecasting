# Retail Demand Forecasting

## Overview

This project focuses on forecasting retail demand using historical sales data from multiple stores and product categories.

The goal is to identify sales patterns, understand demand behavior, build predictive models, and create business-oriented dashboards that support decision-making.

## Dataset

Source: Kaggle - Store Sales Time Series Forecasting

Dataset characteristics:

* 3,000,888 records
* 54 stores
* 33 product families
* Historical data from 2013 to 2017
* Daily sales information

## Project Structure

```text
retail-demand-forecasting/
│
├── notebooks/
│   └── 01_data_understanding.ipynb
│
├── data/
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Power BI

## Current Progress

### Phase 1 - Data Understanding

Completed:

* Data loading
* Data type validation
* Missing value analysis
* Duplicate analysis
* Dataset overview

Key findings:

* No missing values detected
* No duplicate records found
* 31.3% of observations contain zero sales
* Sales distribution is highly right-skewed
* Data spans from January 2013 to August 2017

## Next Steps

* Exploratory Data Analysis (EDA)
* Time series analysis
* Feature engineering
* Machine learning models
* Power BI dashboard
* Final project documentation
