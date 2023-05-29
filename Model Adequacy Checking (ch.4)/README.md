# Model Adequacy Checking

---

The excercises solved in this repository belong to the Chapter 4: Model Adequacy Checking of "Introduction to Linear Regression Analysis, 5th edition by MONTGOMERY, DOUGLAS C., PECK, ELIZABETH A., and VINING, G. GEOFFREY" (2013). 

This repository contains scripts in Python 3.10 to implement Model Adequacy Checking analysis given a specific csv dataset.

---

### Chapter 4: Model Adequacy Checking Excercises :chart_with_upwards_trend: 

**4.2**Consider the multiple regression model fit to the National Football League
team performance data in Problem 3.1. [Table B.1](https://raw.githubusercontent.com/ramirezramiro/linear-reg/main/Multiple%20Linear%20Reg%20(ch.3)/data(ch.3)/table-b3.csv).

**a.** Construct a normal probability plot of the residuals. Does there seem to
be any problem with the normality assumption?

**b.** Construct and interpret a plot of the residuals versus the predicted response.

**c.** Construct plots of the residuals versus each of the regressor variables. Do
these plots imply that the regressor is correctly specified?

**d.** Construct the partial regression plots for this model. Compare the plots
with the plots of residuals versus regressors from part c above. Discuss the
type of information provided by these plots.

**e.** Compute the studentized residuals and the R - student residuals for this
model. What information is conveyed by these scaled residuals?


**4.4** Consider the multiple regression model fit to the gasoline mileage data in [Problem 3.5](https://raw.githubusercontent.com/ramirezramiro/linear-reg/main/Multiple%20Linear%20Reg%20(ch.3)/data(ch.3)/table-b3.csv)..

**a.** Construct a normal probability plot of the residuals. Does there seem to
be any problem with the normality assumption?

**b.** Construct and interpret a plot of the residuals versus the predicted response.

**c.** Construct and interpret the partial regression plots for this model.

**d.** Compute the studentized residuals and the R - student residuals for this
model. What information is conveyed by these scaled residuals?

**4.12** Consider the simple linear regression model fit to the tank pressure and
volume data in Problem 2.16.

**a.** Construct a normal probability plot of the residuals. Does there seem to
be any problem with the normality assumption?

**b.** Construct and interpret a plot of the residuals versus the predicted response.

**c.** Suppose that the data were collected in the order shown in the table. Plot
the residuals versus time order and comment on the plot.

**4.13** Problem 3.8 asked you to fi t two different models to the chemical process
data in Table B.5 . Perform appropriate residual analyses for both models.
Discuss the results of these analyses. Calculate the PRESS statistic for both
models. Do the residual plots and PRESS provide any insight regarding the
best choice of model for the data?



---


## Content script

- Multiple Linear Regression Functions
- Input Hypothesis commands
    - Input your alpha value:
<code class="orange">alpha = float(input("Select alpha value (α): "))</code>
    - Test Hypothesis H0:
<code class="blue">H0 = float(input("Enter hypothesis value H0: "))</code>

- Data plot with regression lines


---

### Thank you! :turtle: 

[You-Jin Park (朴維鎮) ](https://orcid.org/0000-0002-1006-5380) Regression Analysis (2023)
