# Netflix Stock Predictor

## This program performs a 30-day projection of NFLX's stock price 

Credits:
> - V. Tatan [Stock Analysis with Pandas and Scikit Learn](https://towardsdatascience.com/in-12-minutes-stocks-analysis-with-pandas-and-scikit-learn-a8d8a7b50ee7)
> - R. Anderson [Predict Stock Prices using ML](https://medium.com/@randerson112358/predict-stock-prices-using-python-machine-learning-53aa024da20a)


_Data is collected from Yahoo Finance_

### Features included in model include:
```
1. Adjusted Closing Price (given)
2. Volume (given)
3. High PCT (added) - the percentage of change, (high-low)/closing price
4. PCT Change (added) - how much stock has changed at closing
```

### Scikit models tested:
```
* Linear Regression
* Quadratic Regression, 2 polynomials
* Quadratic Regression, 3 polynomials
* SVM Radial Basis Function (rbf) model
* KNN Regression
```

### Confidence scores:
```
Confidence scores varied, but improved with more features and a shorter forecast time. 
This makes sense as the level of confidence goes down over time and with fewer 
features to feed the model(s). 
```
```
LR < Quad 2 < Quad 1< KNN < SCM
```

### Linear performance graph with forecasting:

Forecasting 1% of data:
![alt text](https://github.com/seanita/School-of-AI/blob/master/stock_predictor/images/Forecast%201%25%20of%20data.png)

Forecasting 2% of data
![alt text](https://github.com/seanita/School-of-AI/blob/master/stock_predictor/images/Forecast%202%25%20of%20data.png)

Forecasting 12.5% of data:
![alt text](https://github.com/seanita/School-of-AI/blob/master/stock_predictor/images/Forecast%2012.5%25%20of%20data.png)

Forecasting 30-days:
![alt text](https://github.com/seanita/School-of-AI/blob/master/stock_predictor/images/Forecast%2030%20days.png)



