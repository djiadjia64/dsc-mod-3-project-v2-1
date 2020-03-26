
# Module 3 Final Project


## Introduction

My overall goal for this project was to choose my own dataset and run classifier algorithms to help model the data. I personally chose the Churn dataset in which information is given about a cellular service provider. There were a bunch of variables included which needed to be cleaned and evaluated for relevancy. After initial cleaning, I ran the data through several classifier algorithms and noted the accuracy and precision of each along with their respective confusion matrixes. 


## The Dataset

** state: state of the customer 

** account length: how long the customer has stayed with the service

** area code: area code of customer

** international plan: boolean has international plan or not

** voice mail plan: boolean has voice mail plan or not

** number vmail messages: # of voice mail messages

** total day minutes: total minutes of service during day

** total day calls: total calls during day

** total day charge: total charge during the day

** total eve minutes: total minutes of service during evening

** total eve calls: total calls during evening

** total charge: total charge during the evening

** total intl minutes: total minutes of service during international calls

** total intl calls: total international calls

** total intl charge: total charge of international calls

** customer service calls: # of calls to customer service

** churn: staying with service or cancelling

1. Decided to drop columns state and phone number. 
2. Turned the boolean values of international plan and voice mail plan to 0 and 1 respectively to make it easier to visualize. 
3. Scanned the dataset for any missing values. 
4. Used a standard scaler to standardize all the data. 

## Algorithms Used

1. XGBoost: Popular algorithm that has won many competitions. Uses gradient boosting methods as well as automatically combs through the dataset for any missing values. 

2. AdaBoost: uses a lot of "stumps" in decision trees and weighs trees differently depending on how hard or easy the task was. 

3. Random Forest: Uses large amount of individual decision trees to reach a conclusion. 

4. Gradient Boost: A less complex version of XGBoost, uses gradient descent similarly. 


## Questions:

1. What are the important features in why people stay? 
2. How are the ways we can increase customer retention?
3. What was the best performing algorithm?

## Question Answers

1. International Plan, Voice Mail Plan, Total Day Charge, Number of Customer Service Calls

2. Promotions, sweet spot of charging between 30-40 dollars, offering more and better customer service calls, getting customers onto international and voice mail plans

3. XGBoost/Gradient Booster