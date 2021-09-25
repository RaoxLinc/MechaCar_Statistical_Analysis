# MechaCar_Statistical_Analysis

A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, we help Jeremy and the data analytics team do the following:

- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
-  Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG
![Summarylm](Resources/images/Summarylm.PNG)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle Lenth and Vehicle ground clearance, statistically likely to provide non-random amounts of variance to the model. 

- Is the slope of the linear model considered to be zero? Why or why not?

The p-Value for this model is 5.35e-11 which is much smaller than the assumed significance level of 0.05% thus is sufficient evidence to reject our null hypothesis. The slope of this linear model is not Zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The R-Squared value is 0.7149, which means that 71.5% of all mpg predictions will be determined by this model. The regression model does predict mpg of MechaCar prototypes effectively. 

![TotalSumPSI](Resources/images/TotalSumPSI.PNG)
![Manlot](Resources/images/Manlot.PNG)

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

In total the meet this design Varience PSI is 62.29 PSI which is well within the 100 PSI. While looking at the 3 lots, lot 1 and 2 both are under the PSI, while when looking at Lot 3 the Varience is 170 PSI. 
