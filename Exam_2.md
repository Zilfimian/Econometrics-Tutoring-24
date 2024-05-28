# Question 1
You are given data from a survey conducted in 2017 on 96 regions in a country. The survey provides the following information:

Poverty Rate (percentage of the population below the poverty line)
Unemployment Rate (percentage of the labor force that is unemployed)
Source: National Statistics Institute, 2017.
Poverty Rate=12.5+1.3×Unemployment Rate

Q1: By how much does the poverty rate increase when the unemployment rate increases by 2 percentage points? Explain why some actual poverty rates might fall below the value predicted by the regression model.
Q2: Question: In a Simple Linear Regression Model (SLRM) of poverty rate on unemployment rate, which of the Gauss-Markov assumptions is very likely to be violated? Explain.
Q3: Question: Given the OLS regression, compute the residual for a region with an unemployment rate of 7% and a poverty rate of 22%.

# Questions 2:
We'll analyze house prices with the following variables:

 - HousePrice: Price of the house (dependent variable)
 - Bedrooms: Number of bedrooms
 - Sqft: Square footage of the house
 - Age: Age of the house (in years)

Suppose we have conducted a survey on 500 houses. The results of the regression analysis with HousePrice as the dependent variable are as follows:

### Model 1

HousePrice
^
 =150000+30000⋅Bedrooms
(Standard errors in parentheses)

### Model 2

HousePrice
^
 =100000+25000⋅Bedrooms+200⋅Sqft
(Standard errors in parentheses)

### Model 3

HousePrice
^
 =110000+24000⋅Bedrooms+190⋅Sqft−1000⋅Age
(Standard errors in parentheses)

Additional statistics:

Sample size (n): 500
Adjusted R-squared values: Model 1 (0.4), Model 2 (0.55), Model 3 (0.60)
Sum of Squared Residuals (SSR): Model 1 (1.2E+10), Model 2 (9E+9), Model 3 (7.5E+9)


a) What is the unit of analysis and the sample size?

b) Postulate the population model of the SLRM

c) Write the OLS line of the SLRM

d) Does the number of bedrooms explain a large fraction of the variability in house prices across houses? Explain.

e) Interpret the estimated coefficients from Model 2

f) Compare the estimated slope parameters associated with Bedrooms between the three models. Could you give an explanation for this happening?

g) Predict the house price for a house with 4 bedrooms, 2000 square feet, and 10 years old using Model 3

h) It has been argued that, controlling for other factors, older houses tend to be cheaper. Is this result consistent with the regression in Model 3? Explain.

i) Which would be your preferred Model? Explain
