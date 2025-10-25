# Machine Learning in Python
Sharing algorithms from my journey to explore Machine learning models:

**Predictive modelling**
1. Linear Regression: [Link](https://github.com/Shefali-Agarwal/Data-Science-Projects/blob/main/Linear_Regression_model_car_price_prediction.ipynb)
   1. EDA and cleaning of data
   2. Visualisation of data to select important features (Chart creation is optimised using loops)
   3. Recursive feature elimination method for the feature selection process
   4. Feature selection by eliminating features having high p-value and high VIF, process optimised using loops and functions
   5. Errors are made sure to be normally distributed by JB test, P-value>1% for 99% significance level  
   6. Finally, the said model is tested on the test group for the final summary

2. Logistic Regression: [Link](https://github.com/Shefali-Agarwal/Data-Science-Projects/blob/main/Logistic%20regression%20Breast%20Cancer%20Detection.ipynb)
   1. EDA and examination of the distribution of the dependent variable in the data
   2. Visualisation of different variables in the data and analysis of their variability for two diagnosis types
   3. Fitting the logistic regression and retaining only the features with p-value<0.05
   4. Evaluation of the model on the test group using the confusion matrix and ROC curve

3. Decision Trees: [Link](https://github.com/Shefali-Agarwal/Data-Science-Projects/blob/main/Decision%20Trees%20Titanic%20Data.ipynb)
   1. Data cleaning and handling of Null values
   2. Correlation of variables and visualisation of data with box plot(numerical variables) and bar chart(categorical variables)
   3. Fitting and visualisation of decision trees with different pruning strategies and selection based on the performance on the test data
   4. Evaluation of the model on the test group using the confusion matrix and classification report
  
4. Random Forest: [Link](https://github.com/Shefali-Agarwal/Data-Science-Projects/blob/main/Random%20Forest%20Credit%20Card%20Data.ipynb)
   1. Data Cleaning, EDA, and data visualisation
   2. Hyperparameter tuning with the help of Random Sampler Cross-Validation technique
   3. Fitting of the Random Forest and evaluation
  
5. XG Boosted Trees: [Link](https://github.com/Shefali-Agarwal/Data-Science-Projects/blob/main/XG%20Boosted%20Trees.ipynb)
   1. Data cleaning, visualisation, and preparation
   2. Using the precision, recall, and threshold curve to find the optimum threshold to get the highest precision for recall above a certain limit.
   3. Fit evaluation with a confusion matrix and metrics such as accuracy, precision, recall, and F1 Score on the training and testing data.
  
6. K Nearest Neighbours: [Link](https://github.com/Shefali-Agarwal/Data-Science-Projects/blob/main/K%20Nearest%20Neighbours-%20Loans.ipynb)
   1. Data cleaning wherein only important columns were kept and all others were dropped
   2. Data preparation with missing values handling and encoding the categorical variables
   3. Using the accuracy score, found and used the optimal k value
