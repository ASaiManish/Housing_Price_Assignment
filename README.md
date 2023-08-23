# Housing Price Assignment
Problem Statement:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. The company is looking at prospective properties to buy to enter the market.

Hence company wants to know

* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.

## Steps involved in building the model:

- Reading and Understanding the Data
- Data Cleaning
- Data Visualization
- Data Preparation
- Recursive feature elimination (RFE)
- Model Building and Evaluation

## Conclusions

**In Ridge regression, optiomal Lamda value and Mean squared error are as below:**
* Lambda - 3
* Mean Squared error - 0.0157785

**In Lasso regression, optiomal Lamda value and Mean squared error are as below:**
* Lambda - 0.0001
* Mean Squared error - 0.0157360

**The Mean Squared Error term of Lasso is slightly lower than that of Ridge. Hence based on Lasso, the factors that generally affect the price are :**
* Zoning classification
* Living area
* square feet
* Overall quality
* Condition of the house
* Foundation type of the house
* Number of cars that can be accomodated in the garage
* Total basement area in square feet
* The Basement finished square feet area

## Contact
Created by ASaiManish- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
