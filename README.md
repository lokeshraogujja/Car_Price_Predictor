# Car_Price_predictor
Predicting the price of the car is an example of Regression.
I took data from kaggle website and stored it in cars.csv(uploaded),preprossed the data and stored it in final_cars.csv(uploaded).
I have used the following model to predict the price:
1) LinearRegression (For more info : https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html?highlight=linearregression#sklearn.linear_model.LinearRegression)

It has an Accuracy of 80%

2) LassoCV(Regularization)(For more info: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LassoCV.html?highlight=lassocv#sklearn.linear_model.LassoCV)

It has an Accuracy of 87%

3) RandomForestRegressor(For more info : https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html?highlight=randomforest#sklearn.ensemble.RandomForestRegressor)

It has an Accuracy of 94%

4) SGDRegressor(For more Info : https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.SGDRegressor.html?highlight=sgdregressor#sklearn.linear_model.SGDRegressor)

It has an Accuracy of 82%

For my Data RandomForestRegressor has more accuracy for test data so it would be a better model for prediction.
