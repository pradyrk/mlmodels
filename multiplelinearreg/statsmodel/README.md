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

- Linear equation of Final model is - y = 810.278991 + (2021.952381 * yr) + (-490.197887 * holiday) + (403.872155 * workingday) + (4509.792037 * temp) + (-1311.312270 * windspeed) + (861.774932 * season_summmer) + (1211.623058 * season_winter) + (443.054019 * mnth_aug) + ( 986.670055 * mnth_sept) +(495.958096 * weekday_sat) +(weathersit_Drizzle * -2504.858694 ) + (weathersit_Misty * -733.632834 )

- The R2 value of prediction on test dataset is 0.7968578238752019 which is pretty much close to the training dataset 



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


