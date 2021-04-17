# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG


•	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Based on the p-values, out of the 5 variables, only vehicle_length and ground_clearance provided a non-random amount of variance to the mpg values in the data. This is due to them being statically significant, due to their p-values being extremely close to 0. This can be seen in the full summary statistics below.

•	Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not considered zero. The slope is specifically -1.04e+02. This is because some of the independent variables impacted the dependent variables to some degree. 

•	Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Based on the R-squared value, this linear model can be considered an effective predictor of mpg of MechaCar prototypes. The R-squared value is .07149, meaning that over 71% of instances the linear model would predict the mpg correctly. 


<img src ="https://github.com/Jafranco96/MechaCar_Statistical_Analysis/blob/main/Resources/mpg%20summary.PNG">




# Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

•	Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?


<img src ="https://github.com/Jafranco96/MechaCar_Statistical_Analysis/blob/main/Resources/total%20summary.PNG">


While looking at the overall summary above, it would seem that all suspension coils meet the design specification of not having a variance exceeding 100 pounds since the overall variance is only 62.29. Yet, while looking at the individual manufacturing lots, pictured below, it becomes apparent that there is more to this story.

<img src ="https://github.com/Jafranco96/MechaCar_Statistical_Analysis/blob/main/Resources/lot%20summary.PNG">



While Lot 1 and Lot 2 suspension coils also individually meet the variance regulation, it can be seen that Lot 3 suspension coils actually do not meet the variance regulation, having a variance of 170. This would not have been able to be identified by just looking at only the overall summary. The action item from this analysis should be for Lot 3 suspension coils to go through a re-design process.

## T-Tests on Suspension Coils

The null hypothesis for these t-tests is that there is a statistical difference between the PSI for each manufacturing lot from the population mean of 1,500 pounds per square inch.
For Lot 1 and Lot 2, this null hypothesis would be failed to reject since the p-values are greater than .05. For Lot 3, the null hypothesis would be rejected since the p-value is less than .05. This corresponds with the previous findings of Lot 3 having much greater variance than the other two lots.

All t-tests can be seen below:


<img src ="https://github.com/Jafranco96/MechaCar_Statistical_Analysis/blob/main/Resources/t-test.PNG">


<img src ="https://github.com/Jafranco96/MechaCar_Statistical_Analysis/blob/main/Resources/t-test%20lot%201.PNG">

<img src ="https://github.com/Jafranco96/MechaCar_Statistical_Analysis/blob/main/Resources/t-test%20lot%202.PNG">

<img src ="https://github.com/Jafranco96/MechaCar_Statistical_Analysis/blob/main/Resources/t-test%20lot%203.PNG">

## Study Design: MechaCar vs Competition

