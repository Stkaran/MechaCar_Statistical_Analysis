# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![](https://github.com/Stkaran/MechaCar_Statistical_Analysis/blob/main/Resources/Deliverable_1.png)

- In order to determine a variable is non-random or not, we look to the Pr(>|t|) value in our chart. Here we can see that, due to their very low values, vehicle length, ground clearance, and the intercept are very unlikely to provide random variance in this model. Therefore, we can determine that they do have a significant impact on the mpg of a car.

- The slope of the model is found by looking at our p-value and how it compares to the significance value of 0.05%. For this model the p-value was 5.35e-11, which is much lower than 0.05% we usually aim. Due to this we can reject the intital null hypothesis and determine the slope of this model is not 0.

- The viabilty of the model is found by looking at the r-squared value. For this model it is 0.7149. This means the about 71% of the variablilty of our dependent variables are explained by this model, which is more than high enough to be considered an effective model.

## Summary Statistics on Suspension Coils

![](https://github.com/Stkaran/MechaCar_Statistical_Analysis/blob/main/Resources/Coil_Sum_Del2.png)

![](https://github.com/Stkaran/MechaCar_Statistical_Analysis/blob/main/Resources/Lot_Sum_Del2.png)

- With all Lots in agregate, their variance of 62 in PSI does fall below the 100 pounds per square inch mark. However, when broken down between all Lots individually, we can see that while Lot1 and Lot2 still pass this requirement, Lot3 does not with its variance sitting around 170.

## T-Tests on Suspension Coils

![](https://github.com/Stkaran/MechaCar_Statistical_Analysis/blob/main/Resources/CoilTtest.png)

![](https://github.com/Stkaran/MechaCar_Statistical_Analysis/blob/main/Resources/Lot3Ttest.png)

- For the t-tests, Lot3 stands out again as it is the only Lot whose p-value is not above 0.05. Because of this we would assume that the average mean of PSI of cars in Lot3 do not actually equal to 1500 and it reaffirms  what we saw previously in our Coil summary table of Lot3's PSI variance being much higher than the other lots.

## Study Design: MechaCar vs Competition

