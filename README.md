# Starbucks-Capstone-Project-Udacity

<img width="698" alt="Screen Shot 2021-01-21 at 2 04 02 PM" src="https://user-images.githubusercontent.com/71035452/105400474-fa086700-5bf2-11eb-9fdc-a37b919e41ff.png">

## Motivation for Project

My motivation for this project is to get a deeper understanding of customer buying behavor using starbucks reward app. And how to make imprivement to get more customer to complete offer.

### Project overview

For this project, three datasets were provided that mimics customers' behavior on Starbucks rewards mobile app. Few times a week Starbucks would send out offers to users that use the mobile app. Each offer has its own expiration date and time. 
Some of the challenges are as follows:-

1. Not all users receive the same offer
2. Not many customers completed the offer
3. Some users might receive the offer never open it but still complete the requirement.

**Business Objective**

The business problem that I would like to solve is how to get more customers to complete the offers and how we can reward the customer that make purchases during the promotional period for their loyalty.

_**Dataset Review**_

Data is contained in three files:
portfolio.json - containing offer ids and metadata about each offer (duration, type, etc.) 
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers complete 

**Following Libraries was used to complete this project**

  -pandas 
  
  -numpy 
  
  -math
  
  -json
  
  -datetime
  
  -matplotlib.pyplot as plt
  
  -seaborn as sns
  
  -sns.set()
  
  -%matplotlib inline

  -from sklearn.preprocessing import MinMaxScaler
  
  -from sklearn.model_selection import train_test_split, GridSearchCV
  
  -from sklearn.tree import DecisionTreeClassifier
  
  -from sklearn.naive_bayes import GaussianNB 
  
  -from sklearn.neighbors import KNeighborsClassifier
  
  -from sklearn.linear_model import LogisticRegression
  
  -from sklearn.ensemble import RandomForestRegressor

**The Process used to complete this project**

1. Business Objective
2. Analyze business problem with  visuals, data exploration understand which features and algorithm will be best.
3. Implement algorithm
4. Present result and write blog post about my findings.

**Summary of result**

Based on all the findings the conclusion is more customers prefer the BOGO( buy one and get one free). Since Bogo promotion is doing better than discount. It's time to revamp the discount promotion to attract more customers which will help to increase completion rate. The current discount promo is spent $10 within 10 days and get $2 reward. This seem like a lot of pressure for customers becuase 10 day is not a long period and it goes by very fast. 
New option for the discount promotion. Example, spend $25 from February 1st to 28th and get $5 in reward for freebee or gift card to spend in the future. By extending the time period, it will give more customers the opportunity to complete the offer and take advantage of the promo. 
For those loyal customers that spend without taking advantage of the offer. A loyalty tracking system should be in place to reward them in the form of freebee when they met promo requirement unknowly. It's like a sweet surprise to appreciate customer for their loyalty.

**Aknowledgement**
Would like to thank starbucks for providing dataset
