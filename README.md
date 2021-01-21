# Starbuck-Capstone-Project-Udacity

<img width="698" alt="Screen Shot 2021-01-21 at 2 04 02 PM" src="https://user-images.githubusercontent.com/71035452/105400474-fa086700-5bf2-11eb-9fdc-a37b919e41ff.png">

**Project overview**

For this project, three datasets were provided that mimics customers' behavior on Starbucks rewards mobile app. Few times a week Starbucks would send out offers to users that use the mobile app. Each offer has its own expiration date and time. 
Some of the challenges are as follows:-

1. Not all users receive the same offer
2. Not many customers completed the offer
3. Some users might receive the offer never open it but still complete the requirement.

**Business Objective** 

The business problem that I would like to solve is how to get more customers to complete the offers and how we can reward the customer that make purchases during the promotional period for their loyalty.

**Datase Review**

Data is contained in three files:
portfolio.json - containing offer ids and metadata about each offer (duration, type, etc.) 
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers complete 

**Follow Libraries was used to complete this project**

import pandas as pd
import numpy as np
import math
import json
import datetime
import matplotlib.pyplot as plt
import seaborn as sns
sns.set()
%matplotlib inline

from sklearn.preprocessing import MinMaxScaler
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.tree import DecisionTreeClassifier
from sklearn.naive_bayes import GaussianNB 
from sklearn.neighbors import KNeighborsClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestRegressor

**The Process used to complete this project**

1. Business Objective
2. Analyze business problem with  visuals, data exploration understand which features and algorithm will be best.
3. Implement algorithm
4. Present result and write blog post about my findings.

