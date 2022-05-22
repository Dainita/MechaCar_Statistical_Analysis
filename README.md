# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/97318406/165199191-5775467b-c8fd-4751-9741-0a6126d4f32f.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Is the slope of the linear model considered to be zero? Why or why not?
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/97318406/165199760-d5850cc0-7a19-42d4-8985-e7063e639afc.png)
![image](https://user-images.githubusercontent.com/97318406/165199987-743ecc29-95db-4e04-9161-3fdef7037273.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Although this requirement is met for all manufacturing lots in total with a variance of 62.29, Lot #3 exceeds the specification with a variance of 170.29.

## T-Tests on Suspension Coils
### Hypothesis(all manufacturing lots)
H<sub>0</sub>: PSI across all manufacturing lots is statistically different from the population mean of 1,500 pounds per square inch.

H<sub>a</sub>: PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.

![image](https://user-images.githubusercontent.com/97318406/165226366-50b5480c-2cf8-4f86-b46f-194962d704ec.png)

Based on the common 0.05 significance level, with the p-value of 0.06028, there is not significant evidence to reject the null hypothesis. 

### Hypothesis(each manufacturing lot)
H<sub>0</sub>: PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.

H<sub>a</sub>: PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.

![image](https://user-images.githubusercontent.com/97318406/165226480-52e70e13-74bc-48dc-ba9a-9936479392b4.png)
![image](https://user-images.githubusercontent.com/97318406/165226600-71212c69-9c68-4f43-83fd-7a67be4514f2.png)
![image](https://user-images.githubusercontent.com/97318406/165228144-441bdadf-f0e9-4f0c-b4e8-4bdeb3bbc64d.png)

Both Lot1 and Lot2 have a p-value greater than the 0.05 significance level, therfore there is not significant evidence to reject the null hypothesis. Lot3 has a p-value of 0.04168 indicating there is less than 5% probability that the null hypothesis is correct. The null hypothesis is rejected for Lot3.

## Study Design: MechaCar vs Competition
The auto industry is flooded with competition. Consumers consider many different factors and the most important factor probably will not be the same for each consumer. 
Fuel efficiency, horespower, maintenace cost, safety rating, each consumer will be interested in a different factor. To truly test MechaCar against the competition, all of the factors need to be considered. 
### Hypothesis

H<sub>0</sub>: MechaCar does not provide a superior product with advantages over the competition.

H<sub>a</sub>: MechaCar provides a superior product with advantages over the competition.

Creating a comparative analysis of data from MechaCar and the competition which includes the determining factors in product superiority would include gathering the data for each competitor, fuel efficiency, horsepower, maintenance cost, and safety rating and performing the summary statistics. 
