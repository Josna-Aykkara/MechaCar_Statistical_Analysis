# MechaCar_Statistical_Analysis
---

## Linear Regression to Predict MPG

-	**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?** - The vehicle length and ground clearance are the non-random variables that impacted the mpg values in the dataset substantially based on the Linear Regression results. The strongest contributor of non-random variance seems to be the vehicle length with a p-value of 2.60e-12. The other strong contributor of non-random variance is the ground clearance with a p-value of 5.21e-8. On the other hand, All Wheel Drive (AWD), Spoiler Angle, and Vehicle Weight does not seem to be variables that would provide random number of variances to the MPG values of the vehicle.

![This is an image]( https://github.com/Josna-Aykkara/MechaCar_Statistical_Analysis/blob/main/Images/Linear%20Reg.JPG)

-	**Is the slope of the linear model considered to be zero? Why or why not?** - The slope coefficients hold significant non-zero values and the p-values are less than the significance level of p=0.05. As a result, the slope of the linear model is not zero and would reject the null hypothesis.

-	**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?** - As per the regression model the result of the R-squared value is 0.7149. We can conclude that the model has good quality predictive power for the mpg because values over 0.70 indicate a strong correlation.

## Summary Statistics on Suspension Coils

![This is an image]( https://github.com/Josna-Aykkara/MechaCar_Statistical_Analysis/blob/main/Images/total%20summary.JPG)

-	**The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?** - 
As per the total summary of all the Suspension coils tested, we can encapsulate that the data is ordinarily dispersed because there is no significant variation between the mean and median values of the dataset. Yes, the current manufacturing data meet this design specification for all manufacturing lots in total because the total summary -variance for all the lots is only 62, which is lower the value 100. 

![This is an image]( https://github.com/Josna-Aykkara/MechaCar_Statistical_Analysis/blob/main/Images/Lot%20summary.JPG)


As per the lots individually, Lot 1 and Lot 2 meet the design specification for manufacturing because the respective lots have a variance of 0.979 and 7.469. The variance value of Lot 3 is elevated and exceeds design satisfaction by 170.286 and as a result it doesn’t meet the design requirement. 

## T-Tests on Suspension Coils

![This is an image]( https://github.com/Josna-Aykkara/MechaCar_Statistical_Analysis/blob/main/Images/T-Tests%20summary.JPG)

As per the T-Tests conducted on the suspension coil’s data based on the multiple lots displays a p-value of 0.06, which is higher than the statistical significance of 0.05. As a result, we don’t have necessary evidence to reject the null hypothesis.

![This is an image]( https://github.com/Josna-Aykkara/MechaCar_Statistical_Analysis/blob/main/Images/T-Tests%20by%20lots.JPG)


Manufacturing Lots 1 and 2 are above significance level with p-value of 1 and 0.607

Lot 3 Manufacturing T-Test showed low significance level of p-value of 0.04168, which is enough to reject the null hypothesis.

## Study Design: MechaCar vs Competition

### Overview
The purpose of the statistical study is to test how MechaCar performs against the competition based on the various metrics that would be of interest to the consumer such as:
-	Cost of the vehicle 
-	Maintenance cost 
-	Enhanced Safety features 
-	Efficient engine 
-	Resale value 
-	Mileage on the road (city & highway)
-	Model & style

### Null hypothesis or alternative hypothesis
The null hypothesis would be that MechaCar will not have a significantly higher vehicle mileage than the competitor’s model. The alternative hypotheses would be that MechaCar will have a significantly higher vehicle mileage than that of the competitor’s model.

### Statistical Testing 
The variance test would be a suitable statistical test for the hypothesis. It would enable to compare the mean and median of the MechaCar across all its competitor’s similar class of vehicles.  

### Data for Testing 
The data required to conduct the statistical test would be the mileage of the competitors’ automobiles in the city and highway for similar models and it should be evaluated with MechCar. 


