# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![summary_data_lm.jpg](images/summary_data_lm.jpg)

### Interpretation
1. After producing the summary results of our linear regression model on the MechaCar data, we can see multiple variables that were statistically proven to show non-random amount of variance. The variables that have a big impact on MPG are vehicle length and ground clearance.
2. We can also see that the p-value of our linear model slope is significantly low (5.08e-8); less than our significance level of .05%. This means we have enough evidence to reject the null hypothesis, which means that the slope of our linear regression model is NOT zero. This can also be justified as mentioned earlier, the dependent variable(MPG) is highly impacted by two different variables. This means that the slope cannot be zero, as the dependent variable is not determined purely by random chance.
3. Does the linear model predict MPG of MechaCar prototypes effectively? Statistically, our model is shown to acurately predict MPG. This is shown as our p-value is less than our significance level - reasons mentioned before. We can also see that our r-squared value to be high (.72). The r-sqaured value indicates that 72% of the variability is explained by the regression model.

## Summary Statistics on Suspension Coils
![summary_data_lm.jpg](images/total_summary_table.jpg)<br>
![summary_data_lm.jpg](images/lot_summary_table.jpg)

### Interpretation
The design specifications for the MechaCar suspensions coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. What we can see in a summary statistic table, we can see that the actual variance (62.3psi) of our dataset is significantly less. However, looking at lot 3 of our data set, we can see that the variance(170psi) is significantly greater than 100 psi. This means that lot 3 does not meet specifications.

## Study Design: MechaCar vs Competition
#### T-test comparing all manufacturing lots against the mean PSI of the population
![summary_data_lm.jpg](images/total_ttest.jpg)<br><br><br>
#### T-test comparing each manufacturing lots against the mean PSI of the population
![summary_data_lm.jpg](images/lot_ttest.jpg)

### Interpretation
As we can see, after conducting a T-test comparing all manufacturing lots, we can see that the p-value(.06) is greater than the significane level(.05). Due to this fact, the means of the sample and the population are statistically similar. Looking at the different cases between the lots, we can see that lot 3's p-value(.04) is  less than the significance level(.05). This statistically proves that the means of lot 3 and the population are statistically DIFFERENT. This concludes that lot 3 is not a good representation of the population
