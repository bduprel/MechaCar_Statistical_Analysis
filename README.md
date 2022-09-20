# MechaCar_Statistical_Analysis

## Linear Regression to Predict MP

![LinearRegression](https://user-images.githubusercontent.com/106126621/191150040-203421f6-8b7d-4598-81b2-616881f44dd9.png)
When reviewing the results found above, we can see that vehicle length and ground clearance have a non-random impact on miles per gallon that is statistically significant. This can be seen with p-values of 2.60e-12 and 5.21e-08 respectively. These p-values allow us to reject the null hypothesis. 

Vehicle weight, spoiler angle, and AWD all result in being statistically insignificant with p-values of 0.0776, 0.3069, and 0.1825. This tells us that we cannot comfortably reject the null hypothesis since we are not 95% or more certain the impact on miles per gallon was not random chance. 

The slops of this linear model is non-zero and can be supported by the p-value of 5.35e-11. This is far smaller than the 0.05% requirement needed for a 95% level of certainty.

This model could be used to predict mpg for this new prototype. We find this by looking at the R-squared value of 0.7149 or 71%. This tells us that 71% of predictions can be accounted for with this model. In the world of finance, an R-squared value of 0.7 is deemed to have a strong level of correlation. So with that point of view, this model can be acceptably used to predict mpg. 
