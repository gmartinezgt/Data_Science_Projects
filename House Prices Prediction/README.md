# Predicting Housing Prices: Overview
* Built and trained several models to predict housing prices based on features about the property.
* Cleaned dataset and pruned features by looking at correlation to target variable and intercorrelations.
* Optimized Linear, Elastic Net, and Random Forest Regressors to find the best model.

## Code and Resources Used
**Python Version:** 3.9 <br>
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn

## Results
Linear Regression
* R<sup>2</sup> = 0.82
* RMSE = $32,193.69
* MAE = $21,813.15

Elastic Net Regression
* R<sup>2</sup> = 0.83
* RMSE = $31,939.92
* MAE = $21,272.46

Random Forest Regressor
* R<sup>2</sup> = 0.90
* RMSE = $24,720.52
* MAE = $17,028.20

## Conclusions
* Random forest regression seems to be a superior alternative to linear regression, even with L1 and L2 regularization.
* The random forest regression model was significantly better than the linear regression and elastic net regression models.
* The ensemble nature of the random forest algorithm seems to give it a significant advantage over the other models.
* When it comes to trying to model such a complex market, ensemble models, such as random forest models, seem to have the edge due to its more flexible nature.
