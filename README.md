# MechaCar_Statistical_Analysis# MechaCar_statistical_Analysis

## Background
Jeremy is approached by upper mangement, shortly after starting his new role about a speical project. MechaCar is AutosRU's prototype is suffering from production issues that are preventing the team from their progress. They have called on Jeremy and that data team to review the production data for insights that may help the manufacturing team

## D1 : Linear Regression to predict MPG : Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes

 ![Screenshot Mecha1](https://user-images.githubusercontent.com/89805399/153975698-f72fba49-9dc6-43a0-849c-15a8f7509dc3.png)



Using the MechaCar_mpg dataset  vehicle_length and ground_clearance have signigicant impact on mpg.The linear model prdicts mpg necuase we got the multiple R-squared value is 0.71   

## D2 : Summary Statistics on Suspension Coils Collecets summary statistis on the pounds per square inch (PSI) of the suspension coils from the manufacturing  lots

![Screenshot Mecha2](https://user-images.githubusercontent.com/89805399/153975928-e2b6ba05-0596-4b5a-9e30-67a382ee1064.png)

![Screenshot Mecha3](https://user-images.githubusercontent.com/89805399/153975934-9b2cf7fd-defc-4562-a90b-86cc70969e3e.png)




        The intercept is statistically significant and not zero. The variability may need scaling or tranforming to help improve the predictive power of the model. The design specifications for the MechaCar suspension coils dictate that the variance in total the specifications are met with vaiance of 62.29. By lots

## D3 : T-Tests on Suspension Coils

![Screenshot Mecha4 0 ](https://user-images.githubusercontent.com/89805399/153975955-86798df2-8d98-410d-b8ec-ad864ffccf6a.png)


All lots are not signigiantly different from the population mean

![Screenshot Mecha4 1](https://user-images.githubusercontent.com/89805399/153975966-20fa703b-6919-41f8-8d34-9b84b4d55ddd.png)


Lot 1 is not significantly different from the population mean
        

![Screenshot Mecha4 2](https://user-images.githubusercontent.com/89805399/153975982-afebd43c-b76d-4696-a7fa-2ea08d1fdbd5.png)


Lot 2 is not significantly different from the population mean
        
![Screenshot Mecha4 3](https://user-images.githubusercontent.com/89805399/153975998-92260975-94d4-4a43-bfe9-8c7ccc27c719.png)


Lot 3 is significantly different from the population mean

## D4 : Study Design: MechaCar vs Competition

Hypothesis: Null and Alternative


Null Hypothesis : MechaCar is priced correctly based on its performance 
Alternative Hypothesis : MechaCar is NOT priced correctly based on performance 
Statistical Tests
A multiple linear regression would be used to determine the factors that have the highest correlation/predictability with the list selling price 
(dependent variable); which combination has the greatest impact on price


