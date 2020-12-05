# Fall20_MSBD_5001_kaggle_20720723_TanLifeng

5001 individual project (https://www.kaggle.com/c/msbd5001-fall2020) Language : **python3**

Package:**numpy, pandas, datetime, xgboost, lightgbm, sklearn, joblib, matplotlib**

For each submission, run as follow: **Feature engineering.py, XGBoost.ipynb** 

## Feature engineering (Feature engineering.ipynb)

Raw data: **train.csv, test.csv**

Feature Extraction: run **Features.ipynb** save the new dataset

New dataset: **new_test.csv, new_train.csv** 

I firstly do the data analysis and plot figures to find trends.

After that I extract 12 features. The highest correlationship feature is "if_rush_hour", since I found that hours of 6-20 is not rush hour, while other hours is.

## Training model &Prediction (XGBoost.ipynb)

After comparing several models using cross validation, I chose xgboost as my baseline models and did fine tuning on it. By using GridSearchcv, I got one models.

run **XGBoost.ipynb** and save fine-tuning model in **xgb_14.pkl**.

My final submissions is **reslut_xgb.csv**



* pay attention to the file path

