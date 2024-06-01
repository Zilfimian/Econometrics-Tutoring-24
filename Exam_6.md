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


Find and discuss the specification error the first model is suffering. Explain it using the estimation results of the above table.



# Question 4
We have the following estimated regression model that explains the behavior of profits:

$$\hat{profit}_i = 215 + 14 \cdot sector_i - 22 \cdot home_i - 50 \cdot south_i + 45 \cdot urban_i$$

Such that:
- **profit** is monthly profits in thousand dollars,
- **sector** is a sector dummy variable with a value of 1 if the sampled company belongs to the tertiary sector,
- **home** is a nationality dummy variable equal to 1 if the sampled company is a national company,
- **south** is a dummy variable with a value of 1 if the sampled company is located in the south of the country,
- **urban** is a dummy variable with a value of 1 if the sampled company is located in an urban area.

### a. 

Find the predicted average profit for a foreign manufacturing company that is located in a rural area at the north of the country.

### b. 

Taking two companies of our sample, find the estimated average difference in their monthly profit if we know that one of them is a national manufacturing company located in a southern city of the country and the other one is a foreign services company located in a northern city of the country.


# Question 5

# Wage Equations Analysis for Vietnam Workers

The following wage equations have been estimated using data on workers from Vietnam:

$$\log(salary) = 1.25 + 0.15 \cdot gender + 0.02 \cdot exp$$

$$(0.35) \quad (0.03) \quad (0.004)$$

$$\log(salary) = 1.55 + 0.10 \cdot gender + 0.015 \cdot exp - 0.0005 \cdot (gender \times exp)$$

$$ (0.48) \quad (0.05) \quad (0.005) \quad (0.002)$$

Where:
- **salary** is measured in US dollars,
- **gender** is a dummy variable taking the value of 1 if the worker is male and 0 if the worker is female,
- **exp** measures the years of work experience.


### a. 

What is the estimated average difference between a man's salary with 5 years of work experience and that of a woman's with 10 years of work experience according to the first model?

### b.

What is the estimated average difference between a man's salary with 5 years of work experience and that of a woman's with 10 years of work experience according to the second model?

### c. 

Test that the salary difference between men and women does not depend on experience. (Test whether the effect of experience on wages is the same for both men and women.)

# Question 6

Evaluate in which of the below cases, you can say that the presented results are compatible and explain why:

Note: ρ is correlation coefficient

### a) Cov(x, y) = 25.33 and ρ = -0.37

### b) $s^2(x) = 1,000$, $n = 50$, $\sum x_i = 5,000$ and $CV(x) = 0.316$

### c)  ρ = 0.775 and the graph below

![EX7.jpg](https://github.com/Zilfimian/Econometrics-Tutoring-24/blob/main/EX7.JPG)


# Question 7

The Spanish National Health Commission has conducted a survey to investigate how obesity can affect health. For that purpose, they gather information about the general level of health, which is an index variable that ranges from 1 to 5, with 1 being a self-reported very bad level of health and 5 a very good level of health. Moreover, they collect information on the Body Mass Index (BMI), which is a value derived from the weight and height of an individual (it is defined as the body mass divided by the square of the body height). The resulting random sample contains the responses of 13,374 adults between 20 and 65 years old.

The following model is estimated by OLS using health as the dependent variable:

$\hat{health}_i = 3.288 - 0.024 \cdot BMI_i$
$n = 13374$
$\sum (residuals^2) = 35980$
$\sum (actuals - mean(actuals))^2 = 29325$

## Questions

### Q1. BMI helps explain __% of the total variability of health for this particular sample of individuals.
a. 0.815  
b. 18.5  
c. 81.5  
d. 22.7

### Q2. Which of the following is an algebraic property of Ordinary Least Squares (OLS) of this model?
a. The sum, and therefore the sample average of the OLS residuals, is positive.  
b. The point \((\bar{health}, \bar{BMI})\) is above the OLS regression line.  
c. The sample mean of the actual values of health is equal to the sample mean of the predictions.  
d. The sum of the OLS residuals is negative.

### Q3. Choose the correct interpretation of the slope coefficient:
a. When BMI equals zero, the average level of health is 3.288.  
b. For every additional unit of BMI, the average level of health is predicted to decrease by 0.024%.  
c. When BMI equals 10, the average level of health is 3.048.  
d. For every additional unit of BMI, the average level of health is predicted to decrease by 0.024 units.

### Q4. If Mary’s BMI is 20 and her reported level of health is 3, the model yields a residual for Mary of:
a. -0.288  
b. 2.808  
c. 0.192  
d. -0.480

### Q5. The OLS estimator of this model is likely to be biased because __
a. The variance of BMI is zero.  
b. The correlation between BMI and the error component is different from zero.  
c. The variance of BMI is positive.  
d. The relationship between health and BMI is linear.




   

