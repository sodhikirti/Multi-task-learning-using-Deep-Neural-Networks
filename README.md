# Multi-task-learning-using-Deep-Neural-Networks
Deep learning for simultaneous Classification and Regression

This project is to use Deep Neural Networks for simultaneous multi-task learning of both classification and regression.
For example: It can be used in predicting the gender (2 classes) and age (number) of a person.
Note that both the layers are getting the same set of data to produce outputs.
The loss function in this type of problem is the weighted sum of classification and regression loss
          Loss = w1L1+w2L2

This model can be used for a hurdleregression task as well where the target data is in semicontinuous format (meaning having lot of zeroes or ordinal points)
In such a case our output would be the classification_prediction * regression_prediction
          Net_Output = y_pred_clf * y_pred_reg
HurdleRegression helps to predict zeroes correctly which a normal regression model cannot due to the skewness in the target distribution.

I hope this helps!
