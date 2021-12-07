# MechaCar_Statistical_Analysis

## DELIVERABLE 1
## Linear Regression to Predict MPG

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
We can see that the vehicle length (2.60e-12), and vehicle ground (5.21e-08). In other words, the vehicle length and vehicle ground have a significant impact on miles per gallon. 

### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model considered cannot consider to be zero because the intercept is statistically non-significant -1.040e+02.
When an intercept is statistically significant, it means that the intercept term explains a significant amount of variability in the dependent variable when all independent variables are equal to zero.
This is not our case.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
We can say that this linear model predicts mpg of MechaCar prototypes effectively because the r-squared value is around 0.7149. this mean that 71% of all mpg predictions will be determined by this model.

## DELIVERABLE 2

### The p-value and the r-squared value for the linear regression model![The p-value and the r-squared value for the linear regression model](https://user-images.githubusercontent.com/89410157/144967081-4430ee95-b8cf-4dd8-8da7-ace7534f499f.png)

### Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The global manufacturing data meet the specification for all manufacturing lots because the variance is equal to 62.29, so it meet the 100 PSI variance.

### The mean, median, variance, and standard deviation of the suspension coil’s PSI column![The mean, median, variance, and standard deviation of the suspension coil’s PSI column](https://user-images.githubusercontent.com/89410157/144967197-0b541df8-acbe-4613-a063-13b580d2518c.png)

However, when we look closely the data and analysis by lot, we see that the input of each lot to the variance is very disproportionate. Lot 1 and lot 2 are very low respectively 0.98 and 7.5. So, the requirement are meet with the lot3 which is very high (170.29). 

### lot_summary dataframe using the group_by() and the summarize() functions to group each manufacturing lot![lot_summary dataframe using the group_by() and the summarize() functions to group each manufacturing lot](https://user-images.githubusercontent.com/89410157/144967386-8bbe9ef1-8af1-4347-aed0-a9fadf598411.png)

## Deliverable 3 
### Use t.test() to determine if the PSI across ALL lots is statistically different from the pop. mean of 1,500 PSI
If we take a significance level of 0.05, we can say that for lot 1 we fail to reject the null hypothesis as the p-value is equal to 1. The lot has a relatively small confidence interval.
### lot 1 result
![lot 1 result](https://user-images.githubusercontent.com/89410157/144967931-522b9f91-5269-4969-9ad0-63b2b627282a.png)

The founding are the same for lot 2, we fail to reject the null hypothesis as the p-value is over the significance level of 0.05 equal to 0.6072
### lot 2 result
![lot 2 result](https://user-images.githubusercontent.com/89410157/144968142-04b2f5f9-0938-42fe-86b1-8492d6e3d6e1.png)

We have different founding regarding lot 3. The p-value is 0.04168, so under the significant level of 0.05.  the confidence interval for the third lot does not include the predicted population mean.

### lot 2 result
![lot 3 result](https://user-images.githubusercontent.com/89410157/144968268-58c279f5-e68e-46d1-bf39-d0f160ec3709.png)

## Deliverable 4
With the development of the car industry, we can analysis all the manufacturers are trying the make more efficient car. But performance need most of the time a lot of energy. So, we can analyze the relation between horsepower and the oil consumption of the car.
 Oil consumption: independent variable
Horsepower: dependent value 
Are the Horsepower related the oil consumption of the car : null hypothesis.



