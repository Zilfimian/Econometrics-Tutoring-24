# Question 1
## 1.1
Let $x_1, x_2, \ldots, x_n$ be a random sample of size $n$ taken from $\mathcal{N}(\mu, \sigma^2)$.

a. Show that the sample mean $\bar{x}$ and $\frac{1}{2}(x_1 + x_2)$ are unbiased estimators of $\mu$.

b. Which one is more effective?


## 1.2

Let $X$ be a random variable with $\mathbb{E}(X) = \mu$ and $\text{Var}(X) = \sigma^2$.

We have information about four independent observations: $x_1, x_2, x_3, x_4$.
Let $\hat{\mu}_1 = \frac{1}{4}(x_1 + x_2 + x_3 + x_4)$ be an estimator for the population mean.
**Note: Cross covariances are zero because the observations are independent.**

a. Find $\mathbb{E}(\hat{\mu}_1)$ in terms of $\mu$.

b. Find $\text{Var}(\hat{\mu}_1)$ in terms of $\sigma^2$.

Now consider a second estimator for the population mean μ̂2 being defined as:

 $$\hat{\mu}_2 = \frac{1}{8}x_1 +  \frac{1}{8}x_2 +  \frac{1}{4}x_3 +  \frac{1}{2}x_4$$

Show that this second estimator is also an unbiased estimator for the population
mean. Find its variance.

c. Discuss the sufficiency of both estimators $\hat{\mu}_1$ and $\hat{\mu}_2$.

d. Based on all previous answers, determine which estimator is preferred and explain why.


# Question 2

Using the data of eight firms, a regression model was estimated to analyze the relationship between investment in thousand Euros $y_i$ and production growth rate in % $x_i$:

$y_i = 3.841 - 0.0812x_i$
$R^2 = 0.466$
$SS = 39.21$
$n = 8$

Standart Errors:

$$(2.12) (0.038)$$

Additionally, two different regressions are estimated. The first one only takes into account European firms within the original sample:

$y_i = -0.372 + 0.108x_i$
$R^2 = 0.976$
$SS = 0.949$
$n = 4$

Standart Errors:

$$(0.782) (0.012)$$

And the second one only takes into account American firms within the original sample:

$y_i = 1.259 + 0.171x_i$
$R^2 = 0.933$
$SS = 1.407$
$n = 4$

Standart Errors:

$$(1.43) (0.032)$$

**Find whether making the distinction between European and American firms helps to understand better the behavior of investment and interpret your results.**


# Question 3

# Analysis of Food Expenditure in the USA

We have the following variables:
- **Y**: Food expenditure in USA.
- **X**: Family income.
- **P**: Price index.

Two different regressions are estimated with the following estimation results (standard errors are in brackets and sample size is 500):

| Regression | Coefficient for X | Coefficient for P | Adjusted R-Squared |
|------------|-------------------|-------------------|--------------------|
| Y / P      |                   | 2.462             |  0.614             |
|            |                   | (0.407)           |                    |
| Y / X; P   | 0.112             | -0.739            | 0.978              |
|            | (0.003)           | (0.114)           |                    |

## Specification Error in the First Model

Find and discuss the specification error the first model is suffering. Explain it using the estimation results of the above table.



# Question 4

We have the following estimated regression model that explains the behavior of annual sales:

$$\hat{y}_i = 500 + 20 \, \text{region}_i - 15 \, \text{online}_i - 30 \, \text{domestic}_i + 40 \, \text{urban}_i$$

Such that sales is annual sales in thousand dollars, region is a region dummy variable with a value of 1 if the sampled company is located in the western region, online is a dummy variable that equals 1 if the company primarily sells online, domestic is a dummy variable with a value of 1 if the sampled company is a domestic company, and urban is a dummy variable with a value of 1 if the sampled company is located in an urban area.

a- Find the predicted average sales for a foreign company in the eastern region that primarily sells offline and is located in a rural area.  
b- Taking two companies of our sample, find the estimated average difference in their annual sales if we know that one of them is a domestic company located in an urban area in the western region and the other one is a foreign company that primarily sells online and is located in a rural area in the eastern region.

# Question 5

We have the following information for the annual growth rates (%) in different countries about stock prices (Y) and consumer prices (X):

| Country     | Stock prices (Y) | Consumer prices (X) | Predicted Y | Estimation Residuals | Standardized Residual |
|-------------|------------------|---------------------|-------------|----------------------|-----------------------|
| Australia   | 5.0              | 4.3                 | 7.617       | -2.617               | -0.719                |
| Austria     | 11.1             | 4.6                 | 7.573       | 3.526                | 0.969                 |
| Belgium     | 3.2              | 2.4                 | 7.897       | -4.697               | -1.291                |
| Canada      | 7.9              | 2.4                 | 7.897       | 0.002                | 0.0007                |
| Denmark     | 3.8              | 4.2                 | 7.632       | -3.832               | -1.053                |
| Finland     | 11.1             | 5.5                 | 7.441       | 3.658                | 1.005                 |
| France      | 9.9              | 4.7                 | 7.559       | 2.340                | 0.643                 |
| Germany     | 15.5             | 2.0                 | 7.956       | 7.544                | 2.073                 |
| India       | 1.5              | 4.0                 | 7.662       | -6.162               | -1.693                |
| Ireland     | 6.4              | 4.0                 | 7.662       | -1.262               | -0.346                |
| Italy       | 8.1              | 3.3                 | 7.764       | 0.335                | 0.092                 |
| Japan       | 13.5             | 4.7                 | 7.559       | 5.940                | 1.633                 |
| Mexico      | 4.7              | 5.2                 | 7.485       | -2.785               | -0.765                |
| Netherlands | 7.5              | 3.6                 | 7.720       | -0.220               | -0.060                |
| New Zealand | 4.7              | 3.6                 | 7.720       | -3.020               | -0.830                |
| Sweden      | 8.0              | 4.0                 | 7.662       | 0.338                | 0.092                 |
| UK          | 7.5              | 3.9                 | 7.676       | -0.176               | -0.048                |
| USA         | 9.0              | 2.1                 | 7.941       | 1.058                | 0.291                 |

Knowing that: \(\hat{y}_i = 8.25 - 0.147x_i\)

Answer the following questions:

a- Complete the missing values in the above table.  
b- Show both graphically and formally if the above data suffers from an outlier problem.  
c- If the answer to b is positive, please explain a strategy to solve the problem.






   

