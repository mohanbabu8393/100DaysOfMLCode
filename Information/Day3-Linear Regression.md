# Day 3 - Simple linear Regression

Simple linear regression is a method to predict to dependent variable (Y) based on values of independent variables (X). The two variables 
are related linearly, hence we try to find a linear function that predicts the response value Y.

The equation for the linear regression is 

# y = b0 + b1X1 ,  Y is the dependent variable and X is the independent variable.

Eg: Let us find out life expectancy Y with the number of smoking hours as X

# Best Fit line
In the regression model, we are trying to minimize the errors in the best fit line. We are trying to minimize the length between the observed
Yi and the predicted value yP

min {sum(yi-yp)^2}

# Steps for Implementation:

1. Preprocess the data. - Following the Day 1 procedure to preprocess the data.

2. Fitting the linear regression model to the training set.
          To fit the dataset into the model we will use the linear regression class from sklearn.linear_model library. We create an object regressor
          of LinearRegression class. using the fit() method, we will fit the model into the training set.

3. predicting the result 
          We will predict the observations from the test set. We will save the output in Y_pred.
          
4. Visualisation 
          we will use matplotlib.plyplot to scatter plots of our training sets and test set and see how close our model predicted the values.
          
Done :)
      
