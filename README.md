# StudentizedOLSClassifier
> This is an very old submission I made to the Titanic competition modified to test a custom classifier using some of the old code.
> This custom classifier was created using Scikit Learn's project template for custom estimators.
> It uses statsmodels OLS for the initial fit. Predict then uses the same OLS model to make a 
> prediction. The median of the predictions is subtracted from the prediction to create an estimated 
> residual. The estimated residual is then divided by the standard deviation of the residuals from the fit
> to create an estimated studentized residual. These studentized residuals are then tested against the
> hyperparameter "threshold" to determine the label. All  values greater than or equal to the threshold are 
> labeled True, and values less than the threshold are labeled False.
### This is a work in progress
