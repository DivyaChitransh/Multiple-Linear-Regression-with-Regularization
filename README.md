# Multiple-Linear-Regression-with-Regularization
**Multiple Linear Regression**<br>
This tutorial demonstrate implementation of multiple linear regression.

The key learnings of this tutorial are as follows:

Modeling Linear regression

     - Key learnings
             * loading data set
             * loading libraries from scikit learn
             * creating training and test set enviornment
             * implement linear regression model
             * evaluate linear regression model
             * printing linear regression model in form of equation
             * analysing results
Applying Hypothesis testing

    - Key learnings
            * applying Hypothesis testing
            * analysing results
Overcoming Collinearity, model overfitting and complexity using Regularization

     - Key learnings
             * understanding effect of Collinearity on linear regression model
             * analysing correlation among attributes
             * practical understanding on output of linear regression model in
               presence of correlated festures
             * implement, analyse Ridge regularization to avoid  collinearity,    
               model overfitting and model complexity
             * implement, analyse Lasso regularization to avoid  collinearity,    
               model overfitting and model complexity
             * discovering relevant features using Lasso model 
             * implement, analyse Elasticnet regularization to avoid collinearity, model overfitting and model complexity
             * Analysing results of regularization
             * comparing results of regularization with linear regression model
Hyperparamter tuning via cross validation

     - Key learnings
             * applying cross validation
             * tunning parameters of regularization techniques using cros  
               validation
The data set used for demonstration is Moneyball which can downloaded form https://www.kaggle.com/wduckett/moneyball-mlb-stats-19622012/data . The data has been gathered from baseball-reference.com. It contains following features:

RA: runs allowed<br>
RS: runs scored<br>
OBP: On Base Percentage<br>
SLG: Slugging Percentage<br>
BA: Batting Average<br>
OOBP: opponent’s OBP<br>
OSLG: opponent’s SLG<br>
W: wins in that season<br>
The features from 1-7 are used as indicator variables to predict the outcome W(i.e., wins in season).

The step by step practical learning on implementing and analysing multiple linear regression to predict W is demonstrated below.
