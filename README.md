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

## Summary statistics on suspension coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lots 1 and Lot 2 are within the design specifications and have about the same mean and median.  However, Lot 3 has significant variance and exceeds the manufacturer specification.

## T-tests on suspension coils

Lot 1 and Lot 3 of the PSI values are not different fromm the populaion mean. It appeas that Lot 2 has a p-balue of .347 which indicates that the suspensio coil is different from the population mean.

The following are screenshots from the t-tests:

All lots
<img width="592" alt="All lots" src="https://user-images.githubusercontent.com/93094173/174483087-07beaa19-32b3-4998-9ed5-68df13884b79.png">

Lot 1
<img width="620" alt="Lot1" src="https://user-images.githubusercontent.com/93094173/174483094-98b3e7ed-ccd2-42b1-ab88-5699054e279d.png">

Lot 2
<img width="609" alt="Lot2" src="https://user-images.githubusercontent.com/93094173/174483100-83a42bae-389a-4e72-ad3a-15b6278fdfdc.png">

Lot 3
<img width="759" alt="Lot3" src="https://user-images.githubusercontent.com/93094173/174483112-e3c45d97-2380-445b-8cb2-c685ed3a14be.png">


## Study Design - MechaCar versus the Competition

Customers have varying preferences when they are seeking to purchase a vehicle, so a manufacturer must take into consideration many factors. Some factors to consider are economical considerations such as gas consumption or cost for non-electric vehicles. 

We could evaluate MechaCar's mileage versus a competitor's vehicle. 

H0: MechaCar prototypes' average gas mileage is similar to competitor's vehicles in the same vehicle class Ha: MechaCar average mileage is statistically above or below that of competitor vehicles.

We could use the statistical test of a two-sample t-test.

The data needed would be gas mileage information for both MechaCar as well as the major competitor vehicles that are of the same approximate size in vehicle (e.g. small sized versus larger)
