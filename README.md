# 799-Capstone-Notebooks

Weekly Jupyter notebooks for the DX799 Data Science Capstone. This project focuses on predicting and explaining 2019 U.S. flight delay risk using airline, airport, weather, and BTS delay cause data.

## Weekly Notebooks

- [Week 1: Linear Regression 1](Wk1-JupyterNotebook-Guidinetti.ipynb)
- [Week 2: Linear Regression 2](Wk2-JupyterNotebook-Guidinetti.ipynb)
- [Week 3: Linear Regression 3](Wk3-JupyterNotebook-Guidinetti.ipynb)
- [Week 4: Logistic Regression and Feature Scaling](Wk4-JupyterNotebook-Guidinetti.ipynb)
- [Week 5: Support Vector Machines](Wk5-JupyterNotebook-Guidinetti.ipynb)
- [Week 6: Decision Trees and Random Forests](Wk6-JupyterNotebook-Guidinetti.ipynb)

## Data Sources

The notebooks use the following data sources:

1. 2019 Airline Delays and Cancellations dataset from Kaggle:  
   https://www.kaggle.com/datasets/threnjen/2019-airline-delays-and-cancellations/code

2. BTS Airline On-Time Delay Causes data:  
   https://www.transtats.bts.gov/ot_delay/ot_delaycause1.asp
 
For the BTS data, the filters used were:
- All carriers
- All airports
- January 2019 through December 2019

## Data Files

The notebooks use the following local CSV files:

- `train.csv`
- `test.csv`
- `Flight_delay.csv`

The raw datasets are not included in this repository because the files are too large for GitHub browser upload. The notebooks were run locally with the datasets stored in a `data/` folder using paths such as:

```python
pd.read_csv("data/train.csv")
