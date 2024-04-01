# Sales-Prediction
Project Title: Sales Prediction

Description:

The project utilizes the "Supermarket_sales.csv" dataset obtained from Kaggle for analysis and prediction of sales.

An extensive exploratory data analysis (EDA) is conducted to uncover trends in sales, ranging from the branch with the highest income to the most profitable months. Visualizations such as bar plots, countplots, line charts, pie plots, heatmaps, and joint plots are employed to provide a comprehensive understanding of the dataset.

The EDA serves as a foundation for the subsequent task of sales prediction. Historical sales data from the supermarkets is utilized, and machine learning algorithms are implemented to predict sales totals. The selection of algorithms is based on the continuous nature of the data being predicted.

The dataset is preprocessed, split, tuned, and predictions are made. A 70:30 split ratio is used to divide the dataset into training and test sets. Machine learning algorithms including Linear Regression, Random Forest Classification, and Gradient Boosting are applied to fit the training data and predict total sales values for the test set.

Evaluation metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) Score are calculated for each model. Predicted versus actual values are visualized for each model. The model with the best R2 score is selected and displayed.

Additionally, a feature to generate the importance of features in a graph is implemented. If the best model selected supports the built-in attribute "feature_importances_", the graph is generated; otherwise, it is not.

The accuracy of the models is calculated using the generated R scores, represented as follows:
Linear Regression R-squared (R2) Score: 1.0
Random Forest R-squared (R2) Score: 0.9999154708845687
Gradient Boosting R-squared (R2) Score: 0.9999383758639572