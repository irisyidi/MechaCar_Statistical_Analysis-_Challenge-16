# MechaCar_Statistical_Analysis-_Challenge-16

## Linear Regression to Predict MPG

### Linear Regression Using lm() Function 
![P1-1](https://github.com/irisyidi/MechaCar_Statistical_Analysis-_Challenge-16/blob/main/P1-1.png)

### Summary of Linear Regression Model 
![P1-2](https://github.com/irisyidi/MechaCar_Statistical_Analysis-_Challenge-16/blob/main/P1-2.png)

### Written Summary
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Assume the significance level is 5% , vehicle_length and ground_clearance (as well as intercept) are statistically unlikely to provide a non-random amount of variance. They have a significant impact on mpg. 

- Is the slope of the linear model considered to be zero? Why or why not?

No, the slope of the linear model is not zero because the p value is 5.35e-11, which is smaller than
significant level, 5% we assume. Therefore, there is sufficient evidence to reject the null hypothesis, which means that the slope of our linear model is not zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Yes, the linear model predicrs mpg of MechaCar prototypes. According to the summary output, the r-squared value is 0.71 in multiple regression model while the p value remained significant. According to Pearson correlation coefficient table, mpg and the variables are positively strong correlated.


## Summary Statistics on Suspension Coils

### Total Summary of PSI

![P2-1](https://github.com/irisyidi/MechaCar_Statistical_Analysis-_Challenge-16/blob/main/P2-1.png)

### Lot Summary of PSI

![P2-2](https://github.com/irisyidi/MechaCar_Statistical_Analysis-_Challenge-16/blob/main/P2-2.png)

### Written Summary

The current manufacturing data meets this design specification for all manufacturing lots in total but does not meet that for each lot individually. In the total summary of PSI the variance of PSI is 62.3 which is smaller than 100, which means that the current manufacuturing meets the design specification in total. In the lot summary of PSI, the variance of PSI for lot 1 and lot 2 are 1.0 and 7.5, respecitively but the variance of PSI for lot 3 is 170.3, which is significantly higher than 100, design specification. Therefore, the current manufacturing data does not meet the design specification each lot individually. 

## T-Tests on Suspension Coils

### T-Test across all manufacturing lots
![P3-1](https://github.com/irisyidi/MechaCar_Statistical_Analysis-_Challenge-16/blob/main/P3-1.png)

### T-Test for each manufacturing lots
![P3-2](https://github.com/irisyidi/MechaCar_Statistical_Analysis-_Challenge-16/blob/main/P3-2.png)

![P3-3](https://github.com/irisyidi/MechaCar_Statistical_Analysis-_Challenge-16/blob/main/P3-3.png)

![P3-4](https://github.com/irisyidi/MechaCar_Statistical_Analysis-_Challenge-16/blob/main/P3-4.png)

### Written Summary
Assuming our significance level was the common 0.05 percent, the p-value of all manufacuring lots is 0.06, above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the mean of PSI are statistically equal to 1500.

Assuming our significance level was the common 0.05 percent, the p-value of for PSI in lot 1 is 1, above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the mean of PSI in lot 1 are statistically equal to 1500.

Assuming our significance level was the common 0.05 percent, the p-value of for PSI in lot 2 is 0.6, above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the mean of PSI in lot 2 are statistically equal to 1500.

Assuming our significance level was the common 0.05 percent, the p-value of for PSI in lot 2 is 0.04, below our significance level. Therefore, we have sufficient evidence to reject the null hypothesis, and we would state that the mean of PSI in lot 3 are not statistically equal to 1500.


## Study Design: MechaCar vs Competition.

This study is going to test the fuel efficiency of MechaCar and its competitors. Highway fuel efficiency is an important metric for customers to consider when selecting a car among different car manufacturers because the highway fuel efficiency depends on the fuel consumption and the fuel expenses incurring if using a car. Therefore, the higher fuel efficiency, the better the car is. 

The  purpose of the test is determine whether the sample means are statistically different. Therefore, the null hypothesis is that there is no statistical difference between the two observed sample means and the alternative hypothesis is that there is a statistical difference between two observed sample means. 

As for the data needed to run the statistical test, the highway fuel efficiency of MechaCar and its competitors should be filtered into different tables. 

The statistical test that is used to test the hypothesis is the two sample t-test because the highway fuel efficiency are from different manufacturers in datasets and unpaired t-test is used to compare the mean between two independent groups. 

