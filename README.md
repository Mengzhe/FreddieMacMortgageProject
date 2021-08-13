# Freddie Mac Mortgage Project
In this work, we consider 30-year fixed-rate mortgages (from Freddie Mac mortgage dataset) and aim to predict whether the mortgage will be "paid off" or "charge off". The complete report can be found at my personal website: [https://sites.google.com/nyu.edu/mengzhehuang/data-science-projects/freddie-mac-mortgage-default-prediction-using-monthly-performance-data](https://sites.google.com/nyu.edu/mengzhehuang/data-science-projects/freddie-mac-mortgage-default-prediction-using-monthly-performance-data) 

The main steps are as follows:
1) filter mortgages and only terminated (paid-off or charge-off) loans remain; preprocess data, e.g., handle missing values
2) create windowed (time series) dataset for monthly-update performance data and economic factors
3) build, train and evaluate a neural network model

These steps correspond to the jupyter notebooks. 
