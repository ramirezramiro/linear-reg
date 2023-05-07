# Multiple Linear Regression

---

The excercises solved in this repository belong to the Chapter 3: Multiple Linear Regression "Introduction to Linear Regression Analysis, 5th edition by MONTGOMERY, DOUGLAS C., PECK, ELIZABETH A., and VINING, G. GEOFFREY" (2013). 

This repository contains scripts in Python 3.10 to implement Multiple Linear Regression analysis given a specific csv dataset.

---

### Chapter 3: Multiple Linear Regression Excercises :chart_with_upwards_trend: 

**3.5** Consider the gasoline mileage data in [Table B.3](https://raw.githubusercontent.com/ramirezramiro/linear-reg/main/Multiple%20Linear%20Reg%20(ch.3)/data(ch.3)/table-b3.csv).

**a.** Fit a Multiple Linear Regression model relating gasoline mileage ***y (miles per gallon)*** to ***engine displacement x1*** and the number of  ***carburator valves x6*** 

**b.** Construct the analysis-of-variance table and test for significance of regression.

**c.** Calculate ***R_sq*** and ***R_sq_adj*** for this model. Compare this to the  ***R_sq*** and ***R_sq_adj*** for the Simple Linear Regression model relating mileage <em>y</em> to engine displacement <em>x1</em> in Problem 2.4.

**d.** Find a 95% CI for ***β1**

**e.** Compute the t statistics for testing ***H0:β1 = 0*** and ***H0:β6 = 0***. What conclusions can you draw?

**f.** Find a 95% CI on the mean gasoline mileage when ***x1 = 275 cubic_in*** and ***x6 = 2 barrels***.

**g.** Find a 95% prediction interval for a new observation on gasoline mileage when ***x 1 = 257 cubic_in*** and ***x6 = 2 barrels***.


**3.23** Suppose that a linear regression model with ***k=2 regressors*** has been fit to ***n=25 observations*** and ***R_sq= 0.90***.

**a.** Test for significance of regression at ***α=0.05***. Use the results of the previous problem.

**b.** What is the smallest value of ***R_sq*** that would lead to the conclusion of a significant regression if ***α=0.05***? Are you surprised at how small this value
of ***R_sq*** is?

**3.24** Show that an alternate computing formula for the regression sum of squares in a linear regression model is

![phppANCcD](https://user-images.githubusercontent.com/88079078/236686935-64fcfe89-9c8e-4247-bffb-688053aadfc8.png)


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
