# MechaCar

MechaCar is suffering from production troubles that are impeding the manufacturing team's progress. We have been asked to review production data for insights that will help the manufacturing team at AutosRUs.

In this challenge, I conducted the following analysis:

1. Multiple linear regression to identify which variables in the dataset predict the mpg of MechaCar prototypes.

2. Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.

3. Run t-tests to determine if the manufacturing lots are statistically different from mean population.

4. Design a statistical study to compare vehicle performanfe of the MechaCar vehicles against vehicles from other manufacturers.

## Linear regression to preduct MPG

The weight of the vehicle, AWD, and spoiler angle predicted a non-random amount of variance. Also, the variables that had the most sigificant random variance were the ground clearance and vehicle length.

The slope is not zero giben that we look at the p-value it is less than 0.05.

The R-squared value is 71% meaning that about 71% of the time the model is accurate in predicting the mpg values correctly. Note that there may be other factors that could contribute to the mpg variability as well that may have been omitted from this dataset.

