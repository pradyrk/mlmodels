# Bike Sharing - Linear Regression


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 




## Business Goal 

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions
- The top 3 features based on the +ve coefficient value are,
      -   temp
      -   mnth_sept
      -   Season_winter

- Linear equation of Final model is - y = 732.580867 + (2019.177809 * yr) + (-512.798254 * holiday) + (407.901920 * workingday) + (4942.056768 * temp) + (-1347.183854 * windspeed) + (689.878388 * season_summer) + (1113.750375 * season_winter) + (-334.255523 * mnth_jul) + ( 786.004550 * mnth_sept) +(510.312734 * weekday_mon) +(weathersit_Drizzle * -2505.378688 ) + (weathersit_Misty * -719.702118 )

- The R2 value of prediction on test dataset is 0.7955789654753544 which is pretty much close to the training dataset 



## Technologies Used
- python - Version 3.10.0
- pandas - Version 2.1.3
- seaborn - Version 0.12.0
- sklearn - Version 1.3.0
- sstatsmodels - Version 0.14.0



## Acknowledgements
Give credit here.
- Analytics vidhya was referred to understand few concepts 


## Contact
Created by [@githubusername] - feel free to contact me!


