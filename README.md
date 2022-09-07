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

### Summary Statistics on Suspension Coils


Total_Summary:

![Suspension total summary](https://user-images.githubusercontent.com/105381777/188293566-4252d157-be49-4355-b471-6086c1238f74.PNG)

Lot_Summary:

![Suspension lot summary](https://user-images.githubusercontent.com/105381777/188293567-7c5b1bb6-2a99-43c3-ac40-789704866e5e.PNG)

- The Variance int he Total_Summary is under 100 PSI meeting the specificaions, however in the Lot_Summary we can see that there is
  a problem with Lot 3 with an statistical Varicance of 70.29 more than the 100 acceptable threshold.
  
  ### T.test_Suspension Coils
  
  Suspension Coils T-test
  
  The results for the suspension coils for all manufacturing losts shows no difference from population mean and the p-value is not 
  too low, therefore the null hupothesis is not rejected.
  
  ![t,test suspension coilPSI](https://user-images.githubusercontent.com/105381777/188295878-37714900-edeb-423b-9b24-eecc474c6949.PNG)
  
  
T.test results for lot1 do not show an statistical diffence from the mean polulation and the p-value is not low enough to reject the
null hypotheis.

![t test lot1 PSI](https://user-images.githubusercontent.com/105381777/188296049-71dbeaaf-4164-4773-ab1f-ac99132184d3.PNG)

T.test results as shows below for lot2 do not show values to reject the null hypotheis.

![t test lot2 PSI](https://user-images.githubusercontent.com/105381777/188296149-81a6945e-7121-4a4c-8f66-ae52caa8d453.PNG)

T.test results for Lot3 with a slightly statistical difference from the population mean and the p-value low (0.0417) the null
hypotheis is rejected.

![t test lot3 PSI](https://user-images.githubusercontent.com/105381777/188296296-406c4d66-9113-4664-8059-8788e75e326c.PNG)

## Study Design: MechaCar vs Competition

MechaCar should consider performing various categories comparing the competition, such are city or highway fuel efficiency, maintenance cost, or 
safety rating.
Metric to test:  fuel efficiency, maintenance cost, safety rating, by brand car size and brand.
The averages of different cars in this categories can be compared to the average of MechaCar cars to find the the null hypothesis or altenate
hypothesis. ANOVA test should be consider for this testing.
Data needed to perform this test will be fuel efficiency, maintenance cost, safety rating of MechaCar prototypes.










  
  
  
  



