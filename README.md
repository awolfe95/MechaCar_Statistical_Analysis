# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

* Vehicle length and ground clearance (as well as intercept) provided a non-random amount of variance to the mpg values in the dataset. 
* The slope of the linear model is considered to be zero because the intercept it statistically significant. 
* The linear model does predict mpg of MechaCar prototypes effectively because the r-squared value is .71 and he p-value remained significant. 

## Summary Statistics on Suspension Coils
* Currently, the design specification that the variance of suspension coils must not exceed 100 pounds per square inch is met in total because the total variance is 62.29. However, Lot 3 does not meet this specification because its variance is 170.29. Lots 2 and 3 do meet this specification. 

## T-Tests on Suspension Coils
* The t-test performed on the total PSI had a p-value of .06, which is higher than the signifigance level of .05 and thus the two means are statistically similar. (https://github.com/awolfe95/MechaCar_Statistical_Analysis/blob/main/t-test%20images/total_ttest.png)
* The t-test performed on Lot 1's PSI had a p-value of 1, which is higher than the signifigance level of .05 and thus the two means are statistically similar. (https://github.com/awolfe95/MechaCar_Statistical_Analysis/blob/main/t-test%20images/lot1_ttest.png)
* The t-test performed on Lot 2's PSI had a p-value of .61, which is higher than the signifigance level of .05 and thus the two means are statistically similar. (https://github.com/awolfe95/MechaCar_Statistical_Analysis/blob/main/t-test%20images/lot2_ttest.png) 
* The t-test performed on Lot 3's PSI had a p-value of .04, which is less than the signifigance level of .05 and thus the two means are not statistically similar. (https://github.com/awolfe95/MechaCar_Statistical_Analysis/blob/main/t-test%20images/lot3_ttest.png)

## Study Design: MechaCar vs Competition
* One way to compare the performance of MechaCars and other competitors is the average miles per gallon their cars get. This would indicate how efficient MechaCars are compared to other cars. 
* The null hypothesis for this experiment would be that the there is no difference between the average miles per gallon that MechaCars get comapred to another competitor brand's cars. The alternative hypthesis could be that MechaCars get an average 2 more miles per gallon than another competitors average miles per gallon. 
* To test this, I would use a two-sample t-Test to see if there is a difference between the distribution means of the two sample groups. 
* I would need the miles per gallon column from the MechaCars data. Additionally, I would need to chose a competitor and get their car data, including each cars miles per gallon. 
