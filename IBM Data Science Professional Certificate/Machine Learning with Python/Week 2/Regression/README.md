![Capture](https://user-images.githubusercontent.com/91827137/171032988-cacb4372-bed7-40d6-bf27-14773a8a5561.PNG)

Dependent variables can be seen as: State, Target, Final goal we study and try to predict (X)

Independent variables can be seen as: explanatory variables, the causes of the states (Y)

The regression model relates Y ot dependent variable to a function of X.

The key point is that the `dependent value` should be `continous`. However, the indpependent variables can be measured or either a categorical or continuous measurement scale.

Exapmle:

![Capture](https://user-images.githubusercontent.com/91827137/171033602-58144e5f-04aa-4e6a-8cf1-6bd12869ba79.PNG)

## Types of regression models:
1. Simple regression : when one independent variable is used to estimate a dependent variable. It can be linear or non-linear. 
2. Multiple linear regression: When more than one independent variable is present.

**note**: Linearity of the regression is based on the relationship between the independent and dependent variables.

# Linear regression 
- The approximation of a linear model, used to describe the relationship between two or more variables.  
- There are two variables, dependent variable(Y) and independent variable(X)
- Where we can model the relation   ship between one independent variable (in case of simple linear regression) or two independent variables (In case of multiple linear regression) with the target (Dependent variable) 

***The equation of the line that represents this relationship is:***

![Capture](https://user-images.githubusercontent.com/91827137/171066144-d9e7a21e-2c58-42f8-816e-64a6d0840597.PNG)

### How to draw the line through the points?
### How to adjust the parameters to make the line the best fit for the data?
- Linear regression estimates the coefficient of the line, so we must calculate those values.
- So to make the line fits best, we should adjust the values of b0 and b1.
- To say that this line fits the relationship best, the estimated value(the output of the relationship line) should be close to the actual value(that is given in the data set)
- For example:

![Capture](https://user-images.githubusercontent.com/91827137/171066544-ad8fd0e2-bfdc-4d05-9f95-5751473ea245.PNG)

The differnece between the estimated and the actual output is 90 here, which is bis, that means the prediction line is not accurate, this value (90) is called the residual error.

The error is the difference between the data point and the fitted regression line.

`mathematically`, it can be shown by calculating the ***`Mean Square Error`*** (MSE) which is calculated by this equation:

![Capture](https://user-images.githubusercontent.com/91827137/171066857-42c02bb0-3120-4b26-a6a4-650488c0ec44.PNG)

So, the objective of linear regression is to find a line where the mean of all these errors is minimized. (We should minimize the value of MSE). To so it, we have to find the best parameters b0 & b1.

### How to find values of b0 and b1 that help minimize the MSE ?

![Capture](https://user-images.githubusercontent.com/91827137/171067739-2996031f-0da6-44b2-9446-885ff8e59de0.PNG)

### How can we use it to predict the target variable?
We put the values of b0 and b1 into the equation of Y\`, and passing X1 which is the independent variable, then we can find Y\` which is the estimated value.


