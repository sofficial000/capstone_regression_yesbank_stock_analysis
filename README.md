# capstone_regression_yesbank_stock_analysis
This is the regression of Yes Bank stock closing price prediction.
# Problem statement

Yes Bank is  a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock process of the company and whether Time Series models or any other predictive models can do justice to such situations. This Dataset has monthly stock prices of the bank since its inception and includes closing starting, highest, and lowest stock prices of every month. The main objective is to predict the stock's price for the month.

# conclusion 

All the features are moderately correlated with each other and they are related to the target variable.

The best Algorithm to use for this dataset is Ridge Regressor, the regularization algorithm.

The untuned model was able to explain 95% of variance (R2 score = 0.95) on train set, while the tuned model was able to explain 97% of variance (R2 score = 0.97) on train set which is a tiny improvement of 2 %.

On test set the model performed better untuned with 94% of accuracy, after tuning the accuracy reduced to 93 % .

The Ridge regression is performing even better than Random Forest Regressor. The RFR is giving 90 % accuracy on test data whereas the Ridge is giving 94% accuracy.
