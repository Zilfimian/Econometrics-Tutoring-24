# Question 1
You are given data from a survey conducted in 2017 on 96 regions in a country. The survey provides the following information:

Poverty Rate (percentage of the population below the poverty line)
Unemployment Rate (percentage of the labor force that is unemployed)
Source: National Statistics Institute, 2017.
Poverty Rate=12.5+1.3×Unemployment Rate

Q1: By how much does the poverty rate increase when the unemployment rate increases by 2 percentage points? Explain why some actual poverty rates might fall below the value predicted by the regression model.

Q2: In a Simple Linear Regression Model (SLRM) of poverty rate on unemployment rate, which of the Gauss-Markov assumptions is very likely to be violated? Explain.

[graph is here](https://drive.google.com/file/d/1rJAq0owAZgv8zH4KckR9FayWV9jkAxBB/view?usp=drivesdk)

Q3: Given the OLS regression, compute the residual for a region with an unemployment rate of 7% and a poverty rate of 22%.

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
(Standard errors: 0.5, 0.06)

### Model 2

HousePrice
^
 =100000+25000⋅Bedrooms+200⋅Sqft
(Standard errors in parentheses)
(Standard errors: 0.5, 0.07, 0.25)

### Model 3

HousePrice
^
 =110000+24000⋅Bedrooms+190⋅Sqft−1000⋅Age
(Standard errors: 10, 0.25, 0.25, 0.67)

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


# Question 3

We'll use the following variables:

 - Mileage: Car mileage (dependent variable, measured in miles per gallon)
 - EngineSize: Size of the car's engine (measured in liters)
 - Weight: Weight of the car (measured in pounds)
 - Age: Age of the car (measured in years)

Suppose we conducted a study in 2022 on the main determinants of car mileage. We collected data from a sample of 200 cars. The descriptive statistics are as follows:

![Table 1: Variables Description](https://github.com/Zilfimian/Econometrics-Tutoring-24/blob/main/E2T1.JPG?raw=true)

1. Consider the following OLS regression line:
Mileage^=𝛽0+3.5⋅EngineSize
​OLS estimator of the intercept is___

2. Consider the OLS regression line given below:
Mileage^=35.5−3.5⋅EngineSize
If the Total Sum of Squares of EngineSize equals 100.5 and the unbiased estimator of the error variance equals 9.0, the standard error of the slope is equal to

3. Consider the following OLS regression line:
Mileage^=55.0−2.5⋅EngineSize−0.004⋅Weight−0.8⋅Age
If a car has a mean EngineSize, mean Weight, and mean Age, what is the fitted value of Mileage? 

4. Consider the following OLS regression line:
Mileage^=55.0−2.5⋅EngineSize−0.004⋅Weight−0.8⋅Ag
A car in the sample has an EngineSize of 4.0, Weight of 4000 pounds, and is 5 years old. If its actual Mileage is 22, what is the OLS residual for this car?

5. Consider the following OLS model:
log⁡(Mileage)=0.108+0.032⋅EngineSize+0.117log

If n=200, 𝑅2=0.65, SSR=5, the adjusted R-squared is equal to ___


# Question 4

A research firm has been commissioned by a health and wellness company to develop a model that will help their managers assess the body mass index (BMI) of their clients. They have information on the following variables: BMI (body mass index); weight (weight of the client in kilograms); dwork (distance in kilometers from the client's home to their workplace); age (age of the client in years) and workout (hours spent working out per week). The estimation results are given in the next Table.
OLS estimates - Dependent variable: log(BMI)
|             | Model 1 | Model 2 | Model 3 |
|-------------|---------|---------|---------|
| const       | 2.89    | 2.68    | 2.53    |
|             | (0.036) | (0.056) | (0.072) |
| weight      | 0.015   | 0.012   | 0.011   |
|             | (0.0005)| (0.0005)| (0.0005)|
| log(dwork)  |         | -0.151  |         |
|             |         | (0.018) |         |
| age         |         |         | 0.003   |
|             |         |         | (0.0002)|
| workout     |         |         | -0.005  |
|             |         |         | (0.001) |
| n           | 1199    | 1199    | 1199    |
| R2          | 0.314   | 0.451   | 0.472   |
| SSR         | 147.188 | 117.803 | 113.431 |
Note: Standard errors in parentheses.
Conduct all hypothesis tests at 1 % significance level

a- Interpret the OLS slope coefficient of the SLRM. Is weight statistically significant?  
b- Interpret the estimated coefficient on the variable log(dwork) in Model 2. Is distance statistically significant?  
c- Predict the BMI of a client who weighs 75 kilograms and lives 10 km away from their workplace using Model 2.  
d- How does the effect of weight on BMI change with respect to the estimation result in the SLRM (section a)? Why?  
e- Test whether age and workout are jointly significant.  
f- Test the overall significance of Model 3.  
g- If you were part of the team in the research firm and had to choose a model, which one would you choose and why?
