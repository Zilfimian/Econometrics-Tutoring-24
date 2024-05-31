# Question 1

# 1.1
Given independent random variables \(X_1, X_2, X_3\) with the following properties:

- $E[X_1] = 1, \text{Var}[X_1] = 4$
- $E[X_2] = 2,  \text{Var}[X_2] = 3$
- $E[X_3] = 3,  \text{Var}[X_3] = 5$

a. Expectation of $5X_1 + 2$

b. Expectation of $4X_1 + 2X_2 - 6X_3$

c. Variance of $5X_1 + 2$

d. Variance of $4X_1 + 2X_2 - 6X_3$

# 1.2

Let $Y$ be a random variable with $\mathbb{E}(Y) = \nu$ and $\text{Var}(Y) = \tau^2$.

We have information about five independent observations: $y_1, y_2, y_3, y_4, y_5$.
Let $\hat{\nu}_1 = \frac{1}{5}(y_1 + y_2 + y_3 + y_4 + y_5)$ be an estimator for the population mean.
**Note: Cross covariances are zero because the observations are independent.**

a. Find $\mathbb{E}(\hat{\nu}_1)$ in terms of $\nu$.

b. Find $\text{Var}(\hat{\nu}_1)$ in terms of $\tau^2$.


Consider a second estimator for the population mean $\hat{\nu}_2$ defined as:

$$\hat{\nu}_2 = \frac{1}{10}y_1 + \frac{1}{10}y_2 + \frac{2}{10}y_3 + \frac{3}{10}y_4 + \frac{3}{10}y_5$$

c. Show that $\hat{\nu}_2$ is an unbiased estimator for the population mean $\nu$.

d. Find the variance of $\hat{\nu}_2$ in terms of $\tau^2$.

e. Discuss the sufficiency of both estimators $\hat{\nu}_1$ and $\hat{\nu}_2$.

f. Based on all previous answers, determine which estimator is preferred and explain why.


# Question 2
When conducting a regression analysis, how is the F-statistic calculated for the overall significance test?
- A) The ratio of explained variance to unexplained variance.
- B) The ratio of residual sum of squares to total sum of squares.
- C) The ratio of explained sum of squares to residual sum of squares.
- D) The ratio of total sum of squares to explained sum of squares.

What is the purpose of using dummy variables in regression analysis?
- A) To represent categorical variables with more than two levels.
- B) To remove outliers from the dataset.
- C) To standardize the data before regression.
- D) To create interaction terms between independent variables.


When creating dummy variables for a categorical variable with  k levels, what is the reference category?
- A) The category with the highest frequency.
- B) The first category in alphabetical order.
- C) The category with the lowest frequency.
- D) Any category chosen by the analyst.

What is the interpretation of the coefficient associated with a dummy variable in regression analysis?
- A) The change in the dependent variable when the dummy variable equals 1 compared to the reference category.
- B) The change in the dependent variable when the dummy variable equals 0 compared to the reference category.
- C) The proportion of variance explained by the dummy variable.
- D) The significance level of the dummy variable in the model.


# Question 3

1. Gender distribution in each of the OECD countries in 2010 
2. Inflation rate in each of the OECD countries in 2008
3. Quarterly unemployment rates in the United States from 2000 to 2020
4. Current air quality index in various cities across China
5. Annual GDP growth rate of Japan from 1980 to 2020
6. Per capita income in different states of Brazil in 2021
7. Median house prices in various neighborhoods of London


# Question 4

We have information about the average daily screen time (SCREENTIME = average daily screen time in hours) for 58 individuals combined with information about potential determinants: AGE (age in years), INCOME (monthly income in dollars), EXERCISE (hours of exercise per week), and SOCIAL (number of social interactions per week). Estimation results are presented in the following table:

OLS Estimation Results - Dependent variable: SCREENTIME
| Variable | Model 1 | Model 2 | Model 3 |
|----------|---------|---------|---------|
| Constant | 3.456   | 2.312   | 5.112   |
|          | (0.987) | (0.692) | (0.835) |
| Age      | -0.042  | -0.038  | -0.025  |
|          | (0.011) | (0.014) | (0.016) |
| Income   | 0.001   | 0.003   | 0.002   |
|          | (0.002) | (0.003) | (0.004) |
| Exercise |         | -0.157  | -0.145  |
|          |         | (0.082) | (0.093) |
| Social   |         |         | -0.021  |
|          |         |         | (0.012) |
| n        | 58      | 58      | 58      |
| Adjusted R squared | 0.432   | 0.467   | 0.512   |
| SSR      | 125.342 | 118.678 | 105.456 |
Note: Standard errors are in parentheses.  
Conduct all the hypothesis tests at 1% significance level.

a- Test the individual and global significance in Model 2.  
b- Comment on the effect of INCOME on SCREENTIME in the second model. Why do you think it is a positive and insignificant effect? Does this effect affect the goodness of fit of Model 2 if compared with Model 1? Why?  
c- In Model 3, we add two new explanatory variables: EXERCISE and SOCIAL. Test whether this inclusion helps to improve the quality of the model. Is Model 3 the best in terms of goodness-of-fit? Why?

$$H_0: \beta_3 = 0, \beta_4 = 0$$
$$H_1: H_0 \text{ is not true}$$

d- Are the effects of these two new variables the expected ones?  
e- What about the individual significance of AGE in Model 3 if compared with Model 2? Explain.



