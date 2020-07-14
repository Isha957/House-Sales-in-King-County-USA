# House-Sales-in-King-County-USA
Project on Data Analysis with Python. 
In this Project, we try to analyze the house sales in the King County area based on various factors like:  
      Number of Bedrooms
      Number of Bathrooms
      Square Footage
      Floors
      Basement Sq.Footage
      View
      Waterfront etc.
      

In this project, we retrieve the necessary dataset.
We apply Data pre-processing and Data Preparation stages
We use the function boxplot in the seaborn library to produce a plot that can be used to determine whether houses with a waterfront view or without a waterfront view have more price outliers.

We use the function regplot in the seaborn library to determine if the feature sqft_above is negatively or positively correlated with price.

We fit a linear regression model to predict the price using the feature 'sqft_living' then calculate the R^2.

We fit a Multiple regression model to predict the 'price' using the list of features:
     "floors",
     "waterfront"
     "lat"
     "bedrooms"
     "sqft_basement"
     "view"
     "bathrooms"
     "sqft_living15"
     "sqft_above"
     "grade"
     "sqft_living"
      we then calculate the R^2 value of the above plot.
      
 We further Create a pipeline object that scales the data performs a polynomial transform and fits a linear regression model. Fit the object using the features in the question above, then fit the model and calculate the R^2 value.
      
 We Create and fit a Ridge regression object using the training data, setting the regularization parameter to 0.1 and calculate the R^2 value using the test data.
 
 We then Perform a second order polynomial transform on both the training data and testing data. 
 Create and fit a Ridge regression object using the training data, setting the regularisation parameter to 0.1. 
 Calculate the R^2 utilising the test data provided.
