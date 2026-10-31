# Seattle Weather EDA (2012–2015)

Exploratory data analysis of 1,461 days of Seattle weather data using Python.

## What's inside
- Data quality checks (missing values, duplicates, date range)
- Distributions and outlier detection (IQR)
- Seasonal patterns of temperature and rainfall
- Weather type analysis
- Correlation between variables

## Key findings
- Clear seasonal cycle: warm, dry summers and cool, wet winters
- Precipitation is heavily right-skewed, with about 14% of days flagged as outliers (real storms, so kept)
- Sunny and rainy days each make up about 44% of the data; snow is rare
- Max and min temperature are strongly correlated (about 0.88)

## Tools
Python, pandas, seaborn, matplotlib, SciPy

## Notebook
[Seattle_Weather_Analysis.ipynb](Seattle_Weather_Analysis.ipynb)

## Dataset
Seattle weather, 2012–2015.
