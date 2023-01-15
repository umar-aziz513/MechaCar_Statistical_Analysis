                                            *MechaCar_Statistical_Analysis*

*Linear Regression to Predict MPG*

•	The variables that provided a non-random amount of variance to mpg values are Vehicle length, vehicle weight and ground clearance

•	P value of 5.35e-11is much smaller than the significance level, the null hypothesis is rejected.  So, the slope of the linear model in not zero.

•	Since the R squared value is 0.6825 which is close to 0.7, the linear model will predict mpg of MechaCar prototypes effectively


*Summary Statistics on Suspension coil*

In total, the manufacturing data does meet the design specification since the overall variance is 62 PSI, which is below 100 PSI.  However, after examining the data for manufacturing lot individually, Manufacturing Lot 3 does not meet the design specification since the variance is 170 PSI which is 70 PSI above the limit. 

![You Text](https://github.com/umar-aziz513/MechaCar_Statistical_Analysis/blob/main/Dataframes.png)

*T-Tests on Suspension Coils*

Using the sample size of 150, the p-value turned out to be 0.06 which greater than the significance level 0.05%.  Therefore, null hypothesis cannot be rejected so the sample mean and the population mean are statistically similar.


After doing the Sample testing of Manufacturing Lot1, the p-value turned out to be 1 which much greater than the significance level 0.05%.  Therefore, null hypothesis cannot be rejected so the sample mean of Manufacturing Lot 1 and the mean of the entire population are statistically similar.


After doing the Sample testing of Manufacturing Lot2, the p-value turned out to be 0.607 which much greater than the significance level 0.05%.  Therefore, null hypothesis cannot be rejected so the sample mean of Manufacturing Lot 2 and the mean of the entire population are statistically similar.

After doing the Sample testing of Manufacturing Lot 3, the p-value turned out to be 0.041 which much greater than the significance level 0.05%.  Therefore, null hypothesis cannot be rejected so the sample mean of Manufacturing Lot 3 and the mean of the entire population are statistically similar.
