# MechaCar_Statistical_Analysis

## Linear Regression to Predict MP

![LinearRegression](https://user-images.githubusercontent.com/106126621/191150040-203421f6-8b7d-4598-81b2-616881f44dd9.png)
When reviewing the results found above, we can see that vehicle length and ground clearance have a non-random impact on miles per gallon that is statistically significant. This can be seen with p-values of 2.60e-12 and 5.21e-08 respectively. These p-values allow us to reject the null hypothesis. 

Vehicle weight, spoiler angle, and AWD all result in being statistically insignificant with p-values of 0.0776, 0.3069, and 0.1825. This tells us that we cannot comfortably reject the null hypothesis since we are not 95% or more certain the impact on miles per gallon was not random chance. 

The slops of this linear model is non-zero and can be supported by the p-value of 5.35e-11. This is far smaller than the 0.05% requirement needed for a 95% level of certainty.

This model could be used to predict mpg for this new prototype. We find this by looking at the R-squared value of 0.7149 or 71%. This tells us that 71% of predictions can be accounted for with this model. In the world of finance, an R-squared value of 0.7 is deemed to have a strong level of correlation. So with that point of view, this model can be acceptably used to predict mpg. 

![LotData](https://user-images.githubusercontent.com/106126621/191151822-af8bed84-a4a3-4442-a608-e2f54961a1c0.png)

## Summary Statistics on Suspension Coils

It has been stated to us that the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

The above image of all manufacturing lots shows that we have a variance of 62.29 in PSI. Well within the 100 PSI required by he manufacturer.

However, when this is broken down a bit further by each lot, we can see that Lot 1 is the most consistent with a variance of 0.97. Lot 2 is also acceptable with a variance of 7.46. But Lot 3 raises concerns with a psi variance of 170.28. 
