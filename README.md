# Sales-Prediction

Supermarket_sales.csv is obtained from kaggel and analysed.
The EDA reveals a lot of trends in the sales ranging from which branch has greatest income to which month is the most profitable.
Baplots, countplots, line charts, pie plots, heatmaps, joinplots are generated to get a better visualization of the data in hand.

This EDA then leads to the next part of the project - Sales Prediction.

As a part of this SalesPrediction , I have implemented machine Learning algorithms to predict the sales totals.
The data is first preprocessed, split , tuned and the predictions are made.
The dataset is divided into a training and testset in the ratio 70% :30% and the machine learning algorithms like Linear Regression, Random Forest Classification model and Gradient Boosting are implemented.

I have tried to fit the tarining data in each model to predict the total values for the testset and the metrics like  Mean Squared Error (MSE) , Mean Absolute Error (MAE) and R-squared (R2) Score are calculated from each model.
Predicted vs Actual values are revealed for each model.

The model with the best R2 score is then selected and displayed.
A feature to generate the importance of features in a graph is also implemented. If the best model selected supports the built-in attribute "feature_importances_" , the graph is generated.Else, not.