Hello people! 
I'm Gayatri Vadaparty,

I hereby show you my task submission for Graduate Rotational Internship Program in Sparks Foundation.
As you can see, here is a code for my problem statement.
I chose Task 1 in which we're asked to make a model which can predict 
the score of a student based on the no. of hours he studied.

So, In the first cell, I've used pandas to read and access the given csv data file.
Later on, I've assigned the independent variables in the df to x and the target variable to y.
It's clear that there is one independent variable HOURS 
which can determine the target variable called SCORE.

After that, I've attempted to visualize my data from which i can know 
what regression model can be applied. Like a linear model,or Quadratic model.
or whatever.

I came to know that the data is distributed in a linear fashion. This concluded me to use a Linear Regression model.
from sklearn.linear model I've imported Linear model
One thing to be noted here is, there is a technique called cross validation 
where the given data is splitted as train data and test data in order to increase accuracy of model.

Eventually, i trained the model with train data i.e xtrain and ytrain. Again, I validate my data with the test data.

The values the model predicted were stored in ypred which are
ultimately compared to ytest values for estimating the performance 
of the model.

Using mean_absolute_error or some other metrics in sklearn.metrics, we can estimate the accuracy of our model.

That's it!

Thank you!
