# Machine-Learning-Regression-
Here we will implement all regression models on 1 dataset and will analyze the performance of each model.

and we will discover which regression model is best for that data set by comparing R^2 coefficient of each model.

Adjusted R^2 = R2 shows how well terms (data points) fit a curve or line. Adjusted R2 also indicates how well terms fit a curve or line, but adjusts for the number of terms in a model. If you add more and more useless variables to a model, adjusted r-squared will decrease. If you add more useful variables, adjusted r-squared will increase.
Adjusted R2 will always be less than or equal to R2.

![image](https://user-images.githubusercontent.com/54941875/123754096-21690b80-d8d8-11eb-953d-37c15fe42859.png)
where::-
  N is the number of points in your data sample.
  
  K is the number of independent regressors, i.e. the number of variables in your model, excluding the constant.
