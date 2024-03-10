# Supplement Sales Prediction

This project focuses on predicting supplement sales using various regression models. The dataset used for analysis and prediction is obtained from the [UCI Machine Learning Repository](https://www.kaggle.com/datasets/sureshmecad/supplement-sales-prediction/data). The project is implemented in Python using Google Colab.

## Repository Link
[Supplement Sales Analysis and Prediction](https://github.com/harrisonhys/Supplement-Sales-Analysis-and-Prediction)

## Results

The following table summarizes the performance metrics of different regression models:

| Model                      | MSE       | MAE       | R-squared |
|----------------------------|-----------|-----------|-----------|
| LassoRegression            | 0.032220  | 0.141360  | -0.000058 |
| ElasticNetRegression       | 0.032220  | 0.141360  | -0.000058 |
| AdaBoostRegressor          | 0.018235  | 0.109502  | 0.434018  |
| ElasticNetCVRegression     | 0.015391  | 0.092497  | 0.522296  |
| LassoCVRegression          | 0.015391  | 0.092497  | 0.522297  |
| LinearRegression           | 0.015390  | 0.092497  | 0.522312  |
| RidgeRegression            | 0.015390  | 0.092497  | 0.522312  |
| GradientBoostingRegressor  | 0.013251  | 0.085691  | 0.588704  |
| DecisionTreeRegressor      | 0.011838  | 0.079320  | 0.632584  |
| LGBMRegressor              | 0.011461  | 0.079813  | 0.644287  |
| RandomForestRegressor      | 0.011427  | 0.078165  | 0.645335  |
| XGBoostRegression          | 0.010843  | 0.076751  | 0.663458  |
| CatBoostRegressor          | 0.010807  | 0.076598  | 0.664569  |

## Conclusion

Considering Mean Squared Error (MSE) and Mean Absolute Error (MAE), lower values indicate better model performance. In this case, the CatBoost Regressor model demonstrates the lowest MSE and MAE values among all models.

Furthermore, considering the R-squared value, which indicates how well the model explains the variation in the data, CatBoost Regressor also exhibits the highest R-squared value. This suggests that the CatBoost Regressor model is better at explaining the variation in the data compared to other models.

Based on the evaluation of MSE, MAE, and R-squared, it can be concluded that the CatBoost Regression model is the best model in terms of prediction accuracy and its ability to explain the variation in the data.
