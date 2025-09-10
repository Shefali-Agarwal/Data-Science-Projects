# Machine Learning in Python
Sharing algorithms from my journey to explore Machine learning models:

**Predictive modelling**
1. Linear Regression: [Link](https://github.com/Shefali-Agarwal/Data-Science-Projects/blob/main/Linear_Regression_model_car_price_prediction.ipynb)
   1. EDA and cleaning of data
   2. Visualisation of data to select important features (Chart creation is optimised using loops)
   3. Recursive feature elimination method for the feature selection process
   4. Feature selection by eliminating features having high p-value and high VIF, process optimised using loops and functions
   5. Errors are made sure to be normally distributed by JB test P-value>1% for 99% significance level  
   6. Finally, the said model is tested on test group for final summary

2. Logistic Regression: [Link](https://github.com/Shefali-Agarwal/Data-Science-Projects/blob/main/Logistic%20regression%20Breast%20Cancer%20Detection.ipynb)
   1. EDA and examination of the distribution of the dependent variable in the data
   2. Visualisation of different variables in the data and analysis of their variability for two diagnosis types
   3. Fitting the logistic regression and retaining only the features with p-value<0.05
   4. Evaluation of the model on test group using confusion matrix and ROC curve
