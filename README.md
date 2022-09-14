# MechaCar_Statistical_Analysis

## Deliverable 1: Linear Regression to Predict MPG

<img width="582" alt="Screen Shot 2022-09-08 at 7 53 02 PM" src="https://user-images.githubusercontent.com/104036750/190028459-e3080efb-4583-45ff-aa5a-c35326e68280.png">

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  * vehichle_length and ground clearance provide a non-random amount of variance to the mpg values.
  
* Is the slope of the linear model considered to be zero? Why or why not?
  * The p-value of 5.35e-11 indicates that we should reject our null hypothesis, and that our slope is linear, not zero.
  
* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  * This model isnt extremely effective at predicting mpg given that the Multiple R-squared value is only 0.7149 and the adjusted R-squared value is only 0.6825. 
  
## Delivarable 2: Summary Statistics on Suspension Coils

<img width="471" alt="Screen Shot 2022-09-08 at 7 53 52 PM" src="https://user-images.githubusercontent.com/104036750/190029240-c50e33eb-b934-4289-860e-11d0b1c7c5ee.png">

<img width="327" alt="Screen Shot 2022-09-08 at 7 53 46 PM" src="https://user-images.githubusercontent.com/104036750/190029248-12c38843-a0fd-4322-9471-8581f8a8c353.png">

* The variance of the coilds for the entire population of the production lot is 62.29 PSI which meets the 100 PSI variance requirement. 
  * The variance of lot 1 is 0.98, which satisfies the PSI requirement. 
  * The variance of lot 2 is 7.47, which satisfies the PSI requirement. 
  * The variance of lot 3 is 170.29, which doesn’t satisfy the PSI requirement 
  
## Deliverable 3: ## T-Tests on Suspension Coils

<img width="464" alt="Screen Shot 2022-09-08 at 7 54 52 PM" src="https://user-images.githubusercontent.com/104036750/190029735-d474c29a-25a7-4a47-8216-f3dabe39c462.png">

* Looking at all of the lots, we see that there is a p-value of 0.06. This value is higher than 0.05, therefore, there is not enough evidence to reject the null hypothesis.
+ Lot 1 has a p-value of 1, therefore, we cant reject the null hypothesis.
* Lot 2 has a p-value of 0.61, therefore, we cant reject the null hypothesis.
* Lot 3 has a p-value of 0.04, therefore we can reject he null hypothesis.

## Deliverable 4: Study Design: MechaCar vs Competition

* What metric or metrics are you going to test?
  * Price: Dependent
  * Maintenance costs: Independent
  * Engine type: Independent
  * Safety Rating: Independent
  * MPG: Independent
  
* What is the null hypothesis or alternative hypothesis?
  * Null: The price is correct based on its overall performance.
  * Alternative: The price isn't correct based on its overall performance.
  
* What statistical test would you use to test the hypothesis? And why?
  * Multiple linear regression in order to see what factors have the highest correlation and predictability in regards to price.
  
* What data is needed to run the statistical test?
  * Data on the cars performace in all of the metrics above.
