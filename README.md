# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

  - Linear Model

![Linear Model](https://user-images.githubusercontent.com/96347933/162550626-d46097f1-4cac-43b3-a8da-0db3ea1e71dc.png)

  - Linear Model Summary

![Linear Model Summary](https://user-images.githubusercontent.com/96347933/162550631-a6c511e1-cc47-48b2-938b-99db236b2a10.png)

Vehicle_length and ground_clearance provide non-random variance as p-values are less than 0.05.

The slope is not considered to be 0 because the p-value is below 0.05.

The linear model predicts mpg of MechaCar prototypes effectively because the r-squared value .7149 shows strong correlation.

## Summary Statistics on Suspension Coils

  - Total Summary
 
 ![Total_Summary](https://user-images.githubusercontent.com/96347933/162588211-65caa84e-9cce-4898-a5e0-0ffd76863eb9.png)

  - Lot Summary  
 
 ![Lot_Summary](https://user-images.githubusercontent.com/96347933/162588221-2b98872a-3caf-4311-be25-eb86ed580301.PNG)

Based on the total summary stats of suspension coils the mean PSI is 1498.78, variance 62.29, and standard deviation 7.89.

Lot 1 mean PSI 1500, variance .98, and standard deviation .99
Lot 2 mean PSI 1500.20, variance 7.5, and standard deviation 2.73
Lot 3 mean PSI 1496.14, variance 170.29, and standard deviation 13.05 *This lot has the highest variance and standard deviation which is impacting overall stats

## T-Tests on Suspension Coils

  - Overall T-Test

![Overall_Ttest](https://user-images.githubusercontent.com/96347933/162588735-9c72b4de-dbbb-41f5-bc8c-fb340ba95379.png)

Since the p-value of the t-test is greater than .05 we cannot reject the null hypothesis

  - Individual T-tests

![Lot1_Ttest](https://user-images.githubusercontent.com/96347933/162588740-f6e50b30-0b76-484a-9d89-014ba5faf488.png)

![Lot2_Ttest](https://user-images.githubusercontent.com/96347933/162588746-83a977e2-dcb4-4eb8-874d-69d2c001fb17.png)

Lot 1 & 2 have a p-value that is more than .05 so we cannot reject the null hypothesis.  This indicates that both have a mean that is similar to the population.  Lot 3 has a p-value less than .05 at .04168 making it different that the population mean.
![Lot3_Ttest](https://user-images.githubusercontent.com/96347933/162588752-f372a3e8-b432-4ee8-9d22-90641f56c229.png)

