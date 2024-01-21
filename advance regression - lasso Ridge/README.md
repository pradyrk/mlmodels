# Project Name
> House Price Prediction - Regularization using Lasso and Ridge


 Table of Contents
* [About the Project](#about-the-project)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

 About the Project
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.




 Conclusions
- Lasso Performed better than Ridge and Linear Regression
- Lasso prediction score on train(0.897) and test(0.890) is close to zero variance(0.007)
- Ridge prediction score on train(0.901) and test(0.876) is close to 3% variance
- Linear regression prediction score on train(0.902) and test(0.857) is close to 5% variance
- RMSE value of Prediction on test is slightly lesser for lasso compared to Ridge , smaller the better. So Lasso wins even with RMSE
- In Lasso, some of these coefficients become 0(check the table above), thus resulting in model selection and, hence, easier interpretation
- In Lasso the features which influences the model are displayed in the below table
- The optimized alpha value of Lasso is 0.0001 and Ridge is 0.8



 Technologies Used
- pandas 
- numpy
- matplotlib 
- seaborn
- sklearn
- statsmodels


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

 Acknowledgements
 Knowedge Articles by Analytics Vidya 
 Knowledge Artiles by machinelearningmastery.com
 The knowledge and course content by Upgrad


 Contact
Created by [@pradyrk] - feel free to contact me!


