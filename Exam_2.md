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
Knowing that $\bar{Y} = 0.25$, $\bar{X} = 5$, $\text{Cov}(Y, X) = -0.7$, and $\text{Var}(X) = 0.45$, find the estimated value for the intercept and slope coefficients and interpret your results.


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

Additional Information:
$\sum_{i=1}^{5} (y_i - \bar{y})(x_i - \bar{x}) = -15625$

$SST_x = \sum_{i=1}^{5} (x_i - \bar{x})^2 = 6250$

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

