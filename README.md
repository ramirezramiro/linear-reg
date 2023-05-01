# Simple Linear Regression

---

The excercises solved in this repository belong to the Chapter 2: Simple Linear Regression "Introduction to Linear Regression Analysis, 5th edition by MONTGOMERY, DOUGLAS C., PECK, ELIZABETH A., and VINING, G. GEOFFREY" (2013). 

This repository contains scripts in Python 3.10 to implement Simple Linear Regression analysis given a specific csv dataset.

---

### Chapter 2: Simple Linear Regression Excercises :chart_with_upwards_trend: 

**2.10** The weight and systolic blood pressure of 26 randomly selected males in the age group 25 – 30 are shown [below](https://raw.githubusercontent.com/ramirezramiro/linear-reg/main/Linear-Reg-Data/2-10-2-11.csv). Assume that weight and blood pressure (BP) are jointly normally distributed.

**a.** Find a regression line relating systolic blood pressure to weight.

**b.** Estimate the correlation coefficient.

**c.** Test the hypothesis that ρ = 0

**d.** Test the hypothesis that ρ = 0.6

**e.** Find a 95% CI for ρ

**2.11** Consider the weight and blood pressure data in Problem 2.10. Fit a no -intercept model to the data and compare it to the model obtained in Problem 2.10. Which model would you conclude is superior?

**2.30** Consider the [data](https://raw.githubusercontent.com/ramirezramiro/linear-reg/main/Linear-Reg-Data/2-30.csv) in Problem 2.12 and assume that steam usage and average temperature are jointly normally distributed.

**a.** Find the correlation between steam usage and monthly average ambient temperature.

**b.** Test the hypothesis that H0: ρ=0

**c.** Test the hypothesis that H0: ρ=0.5

**d.** Find a 99% CI for ρ


---


## Content script

<style>
code.blue {
  color: #337AB7 !important;
}
code.orange {
  color: #F7A004 !important;
}
</style>

- Linear Regression Functions
- Input Hypothesis commands
    - Input your alpha value:
<code class="orange">alpha = float(input("Select alpha value (α): "))</code>
    - Test Hypothesis H0:
<code class="blue">H0 = float(input("Enter hypothesis value H0: "))</code>

- Data plot with regression lines


---

### Thank you! :turtle: 

[You-Jin Park (朴維鎮) ](https://orcid.org/0000-0002-1006-5380) Regression Analysis (2023)
