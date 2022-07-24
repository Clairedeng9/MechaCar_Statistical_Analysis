# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/103073631/180669169-79580e31-89dd-4357-babf-7cfb779060da.png)

Write a short summary using a screenshot of the output from the linear regression, and address the following questions:

Firstly, we know the regression can be expressed as below from the screenshot:

`mpg = -0.01 + 6.267(vehicle length)+.001(vehicle weight)+.069(spoiler angle)+3.546(ground clearance)-3.411(AWD).`

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

    From above screenshot, assuming our significance level was the common 0.05 percent, the P-values of vehicle_length and ground_clearance are both less than 0.05, statistically signically, therefore `vehicle_length` and `ground_clearance` provide a non-random amount of variance to the mpg values in the dataset

- Is the slope of the linear model considered to be zero? Why or why not?

    The coefficients of variables show as below. We can also see the multiple linear regression formula above, knowing that even some of variables are closed to zero but we cannot say the slope of the ilnear model considered to be zero.

    ![image](https://user-images.githubusercontent.com/103073631/180669532-5ccc1dac-def1-499a-9635-d0b7b722e55e.png)

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

    We know that F calculated as , the critical values for Fdistribution alpha equals to 0.05, F = 2.427 < 22.07 , also P-value is5.35e-11 less than 0.05, statistically signically. Also, this linear model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. Relatively speaking, the multiple regression model does predict mpg of MechaCar prototypes effectively.
