#### Table of Contents
[[Simple Linear Regression]]
[[Multiple Linear Regression]]
[[Polynomial Regression]]
[[Ridge Regression]]
[[Lasso Regression]]
[[ElasticNet Regression]]

----
The linear model has been the "Mainstay" In machine learning for years, and thus remains one of the most popular supervised learning algorithms to this day. It is a simple yet powerful approach to mainly regression tasks but can somewhat be extended to classification. 
For regression problems, which we will be focusing on here, the model looks to predict a continuous output value.

Linear regression is a model that looks to describe a the relationship between one or more independent variables X and a dependent variable y.

Remember that a straight line has the equation 
$$y=mx+c$$

The idea behind linear regression is to approximate the relationships by approximating a linear function to the data. Meaning fit a line to it.
The aim is therefore to fit a best fitting line, (a line that fits the data the best.)  This is done by selecting the right values for the coefficients in the equation.

Now while It might be obvious which line fits the data the best, visually we would see which line is closest to all the true independent variables We need a mathematical method to quantify how well a model is performing (a quantity that suggests one line is a better model than the other). This is the job of the cost function, while there are a bunch to chose from the most common and the one that will be discussed here is the:

> Mean Squared Error (MSE)

The MSE can be calculated using the formula below:

$$ \text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2 $$
This just finds the mean of the squared residuals (the differences between the model prediction and true data)

For linear regression to yield reliable and accurate results the data it acts upon has to satisfy these assumptions:

[[Assumptions of Linear regression]]

There are a lot of sub branches we can look at that fall under the umbrella of linear regression. These are listed and looked at below:

---
[[Simple Linear Regression]]
[[Multiple Linear Regression]]
[[Polynomial Regression]]
[[Ridge Regression]]
[[Lasso Regression]]
[[ElasticNet Regression]]