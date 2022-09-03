# MechaCar_Statistical_Analysis

## Overview

AutosRUs' new Mechacar is suffering from production troubles and upper management has requested statistical analysis to review
the production data for insights that may help the manufacturing team.

The goal for this data analysis is:
- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each 
  statistical analysis, you’ll write a summary interpretation of the findings.

## Results

### Linear Regression to Predict MPG

![P-Value and r-squared](https://user-images.githubusercontent.com/105381777/188285102-9b2c6bdd-bb3c-46ee-8893-41027f6cbf60.PNG)
- Vehicle Lenght and Ground Clearence are the significant variables in the dataset.  The linear regression model run on these variables 
  against figuresfor MPG resulted in p-values of 2.6 and 5.21, respectively. The intecept was also statistically significant, which
  indicates that likely there are other factors not included in the datase that have a strog inpact on the MPG.
- The null hypothesis must be rejected since the slope of the linear model can not be considered to be zero as ther is 
  a p-value of 5.35.
- The r-squeare value of 0.7149, indicates that the model is at 71% accurate, although there are still unconsidered factors.

