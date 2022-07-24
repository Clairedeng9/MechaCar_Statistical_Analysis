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

## Summary Statistics on Suspension Coils
Write a short summary using screenshots from your total_summary and lot_summary dataframes, and address the following question:

### Manufacturing Lot Summary

![image](https://user-images.githubusercontent.com/103073631/180670293-12847d5f-6e71-42fd-b58f-09faed051c04.png)

### Summary by Manufacturing Lot Number
![image](https://user-images.githubusercontent.com/103073631/180670307-a840c2db-ba48-495d-a929-c45ac36f58fd.png)



- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
    
    From the manufacturing Lot Summary, the variance for the total manufacturing lot is around 62 < 100, which is within the expected design specifications of not exceeding 100 pounds per square inch. However, to see the summary by manufacturing lot summary, Lot 3 is a large contributing factor to the variance being high. Lot 3 shows a variance of 170 > 100 and does not meet the design specifications. Lot 1 and Lot 2 have significantly lower variance, which equal to 1 and 7.


## T-Tests on Suspension Coils

Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
### Entire Lot

![image](https://user-images.githubusercontent.com/103073631/180670562-b8922003-d560-41c4-9cb6-0d8755c49731.png)

### LOT 1

![image](https://user-images.githubusercontent.com/103073631/180670610-c6da27fa-3758-4073-b4e8-a14e2fca9300.png)

### LOT 2

![image](https://user-images.githubusercontent.com/103073631/180670623-76cf5f0e-2950-46b9-a49c-74aca5e8a2f4.png)

### LOT 3

![image](https://user-images.githubusercontent.com/103073631/180670640-1aad371d-05ec-4010-a617-2ff9ad3ada60.png)



