# MechaCar_Statistical_Analysis
Perform multiple linear regression analysis, collect summary statistics, run t-tests, design a statistical study to compare vehicle performance.

## Skill Set:

•	Load, clean up, and reshape datasets using tidyverse in R.
•	Visualize datasets with basic plots such as line, bar, and scatter plots using ggplot2.
•	Generate and interpret more complex plots such as boxplots and heatmaps using ggplot2.
•	Plot and identify distribution characteristics of a given dataset.
•	Formulate null and alternative hypothesis tests for a given data problem.
•	Implement and evaluate simple linear regression and multiple linear regression models for a given dataset.
•	Implement and evaluate the one-sample t-Tests, two-sample t-Tests, and analysis of variance (ANOVA) models for a given dataset.
•	Implement and evaluate a chi-squared test for a given dataset.
•	Identify key characteristics of A/B and A/A testing.
•	Determine the most appropriate statistical test for a given hypothesis and dataset.

## Objectives:

  - Linear Regression to Predict MPG
  - Summary Statistics on Suspension Coils
  - T-Test on Suspension Coils
  - Design a Study Comparing the MechaCar to the Competition

## Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
After importing the data, a level of 95% confidence was set.  The outcome reflects the p-value at .05 level of significance for verification of statistical significance.
![1](https://github.com/vhernandezjr/MechaCar_Statistical_Analysis/blob/main/PNG/LR_1.png)

Is the slope of the linear model considered to be zero? Why or why not?
This is not the case; the slopes of the variables are all unequal to zero. The data above shows no values sit a zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
As the table above shoes the R-squared value equals .7 which implies a strong correlation to the data on hand.  The data on hand must be assumed limited with emerging tech and materials it would need to be constantly evaluated to make accurate predictions.

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
Overall, the variance for all manufactured suspension coil is within the tolerance of the design specifications of staying under 100 PSI.  If we take a closer look at lot 3, we observe the variance is much higher to lot 1 and lot 2 and not within tolerance.

![2](https://github.com/vhernandezjr/MechaCar_Statistical_Analysis/blob/main/PNG/SS_2.png)

## T-Tests on Suspension Coils
For all lots the mean falls within range of the 95 percent confidence level.  The image below verifies this but keying on lot 1 and lot 2 we see a normal distribution.  This leads us to not dismiss the null hypothesis.

![3](https://github.com/vhernandezjr/MechaCar_Statistical_Analysis/blob/main/PNG/TT_3.png)
