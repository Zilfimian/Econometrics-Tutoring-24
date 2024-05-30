# Question 1

Let $\(Y_1\), \(Y_2\), and \(Y_3\)$ be a random sample from a normal distribution where both $\(\mu\)$ and $\(\sigma\)$ are unknown. Which of the following is an unbiased and a more efficient estimator for $\(\mu\)$? 

$\hat{\mu}_1 = \frac{1}{4} Y_1 + \frac{1}{2} Y_2 + \frac{1}{4} Y_3$

$\hat{\mu}_2 = \frac{1}{3} Y_1 + \frac{1}{3} Y_2 + \frac{1}{3} Y_3$

a. unbiased - ?

b. efficient - ?

# Questions 2

The objective of this task is to explore the relationship between sales revenue and advertising spend using a linear regression model.
We denote $Y_i$ as total sales revenue (in million dollars) and $X_i$ represents the advertising spend. We consider the following linear regression model that yields the relationship between sales revenue and advertising spend:

$Y_i = \beta_0 + \beta_1 X_i + u_i$

such that $u_i$ denotes an unobservable error (random perturbances).

### a. Factors in $u_i$
Think about possible factors contained in $u_i$.

### b. Estimation
Knowing that $\bar{Y} = 1.25$, $\bar{X} = 0․15$, $\text{Cov}(Y, X) = 1.7$, and $\text{Var}(X) = 0.45$, find the estimated value for the intercept and slope coefficients and interpret your results.


# Question 3
Suppose the salary of employees in a company is modeled by a simple linear regression model (SLRM) such that:

$y_i = \beta_0 + \beta_1 x_i + u_i \quad \text{for} \quad i = 1, ..., n$

Where:
- $x_i$ represents the years of experience of an employee.
- $y_i$ represents the salary of the employee.

Let's estimate the above function given the sample information in the table below:

| Observation | Years of Experience (x) | Salary (y) |
|-------------|-------------------------|------------|
| 1           | 5                       | 50000      |
| 2           | 2                       | 45000      |
| 3           | 7                       | 60000      |
| 4           | 10                      | 70000      |
| 5           | 3                       | 48000      |


a) Which is the estimated salary function?

b) Calculate the fitted values of the salary and the residuals

c) Compute the sum of residuals

d) Compute the R-squared

# Question 4

The HH's medical expenses are determined by the following estimated regression model:

$\text{log(Medical Expenses)}_i = \beta_0 + \beta_1 \text{Age}_i + \beta_2 \text{log(Number of Visits to the Doctor)}_i + \beta_3 \text{Chronic Conditions}_i$

Where:
- $\text{Medical Expenses}_i$ represents the monthly medical expenses of the HH in Euros.
- $\text{Age}_i$ represents the age of the HH.
- $\text{Number of Visits to the Doctor}_i$ represents the number of visits to the doctor per month.
- $\text{Chronic Conditions}_i$ represents the number of chronic conditions the HH has.

The HH's salary is determined by the following estimated regression model:

$\text{log(Medical Expenses)}_i = 10 + 1.4 \text{Age}_i + 0.9{log(Number of Visits to the Doctor)}_i$

$n=1000, R^2=0.54$

a. Interpret the above estimated model.

b. We reestimate the above model including a new explanatory factor, HH education in years, and we obtain the following estimation results:

$\text{log(Medical Expenses)}_i = 10 + 1.4 \text{Age}_i + 0.9{log(Number of Visits to the Doctor)}_i + 2.4 \text{Chronic Conditions}_i$

$n=1000, R^2=0.64$

Which is the model with a better goodness-of-fit? Why?


# Question 5

Which of the following best describes the concept of multicollinearity in Multiple Linear Regression (MLR)?
- A) It occurs when the residuals are not normally distributed.
- B) It refers to the situation where the relationship between two independent variables is linear.
- C) It indicates a strong correlation among independent variables.
- D) It is a measure of the overall goodness-of-fit of the regression model.

In Multiple Linear Regression (MLR), what does the coefficient of determination (R-squared) represent?
- A) The proportion of total variance explained by the model.
- B) The significance level of the independent variables.
- C) The strength of the relationship between the dependent and independent variables.
- D) The magnitude of multicollinearity among the independent variables.

In a regression analysis, what is the null hypothesis for the t-test associated with an independent variable's coefficient?
- A) The coefficient is equal to zero.
- B) The coefficient is greater than zero.
- C) The coefficient is less than zero.
- D) The coefficient is not significantly different from zero.

When conducting a hypothesis test for the significance of the overall regression model, what is the null hypothesis for the F-test?
- A) The intercept coefficient is equal to zero.
- B) At least one of the independent variables has a coefficient equal to zero.
- C) All independent variables have coefficients equal to zero.
- D) The residuals are normally distributed.


