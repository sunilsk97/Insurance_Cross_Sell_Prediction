# Insurance_Cross_Sell_Prediction

## Problem Statement
Our client is an insurance company that has provided Health Insurance to it's customers. now they need your help in building a model to predict whether the policyholders (customers) from the past year will also be interested in Vehicle insurance provided by the company. An insurance policy is an agreement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is sum of money that the customer needs to pay regularly to an insurance company for this guarantee. For example, you may pay a premium of a Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if, God forbid, you fall ill and need to be hospitalised in that year, the insurance premium will bear the cost of hospitalisation etc. for upto Rs. 200,000. Now, if you are wondering how can company bear such high hospitalisation cost when it charges a premium of only Rs. 5000/-, that is where the concept of probabilities comes in picture. For example, like you, there may be 100 customers who would be paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalized that year and not everyone.This way everyone shares the risk of everyone else.
Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called 'sum assured') to the customer.
Building a model to predict whether a customer would be interested in vehicle insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.
Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code), Vehicles(Vehicle age, Damage), Policy (Premium, sourcing channel),etc.



## CONCLUSION
During our analysis we performed EDA on our data. We have analyzed both numerical as well as categorical columns / features. After performing EDA we got to know that 'Annual_Premium' column have outliers, so, in feature engineering we removed the outliers with the help of IQR method. Also out output column had imbalanced data. So to tackle that thing we performed data-resampling using SMOTE technique. Next we implemented 4 Machine Learning Models and also performed hyperparameter tuning and cross validation for each method. Following are the results of the models :-
- There was overfitting issues while using Random forest method. We tackled that with hyperparameter tuning.
- Annual Premium column has the highest importance among all the features.
- We are getting 85% accuracy for both test and train dataset while using Random Forest model with hyperparameter tuning.
- Hence, we can deploy this model.



### Technologies Used  
![](https://forthebadge.com/images/badges/made-with-python.svg) 
