![cover_updated_28_May-thumbnail-1200x1200](https://user-images.githubusercontent.com/25604111/120116096-12d9e800-c1a4-11eb-954d-09c211aa5dc3.png)


# JOB-A-THON - May 2021
This repo contains the code and approach document related to JOB-A-THON conducted by Analytics Vidhya.
Link to Competition [here](https://datahack.analyticsvidhya.com/contest/job-a-thon-2/?utm_source=datahack&utm_medium=Navbar&utm_campaign=Jobathon).

## Problem Statement
Happy Customer Bank is a mid-sized private bank that deals in all kinds of banking products, like Savings accounts, Current accounts, investment products, credit products, among other offerings. The bank also cross-sells products to its existing customers and to do so they use different kinds of communication like tele-calling, e-mails, recommendations on net banking, mobile banking, etc. In this case, the Happy Customer Bank wants to cross sell its credit cards to its existing customers. The bank has identified a set of customers that are eligible for taking these credit cards.
Now, the bank is looking for your help in identifying customers that could show higher intent towards a recommended credit card, given:
**Customer details (gender, age, region etc.)**

**Details of his/her relationship with the bank (Channel_Code,Vintage, 'Avg_Asset_Value etc.)**

## Data Dictionary

| __Variable__ | __Description__ |
|-------------|------------|
| ID          | Unique Identifier for a row     |
| Gender         | Gender of the Customer |
| Age | Age of the Customer (in Years) |
| Region_Code | Code of the Region for the customers |
| Occupation | Occupation Type for the customer |
| Channel_Code | Acquisition Channel Code for the Customer  (Encoded) |
| Vintage | Vintage for the Customer (In Months) |
| Credit_Product | If the Customer has any active credit product (Home loan,Personal loan, Credit Card etc.) |
| Avg_Account_Balance | Average Account Balance for the Customer in last 12 Months |
| Is_Active | If the Customer is Active in last 3 Months |
| Is_Lead(Target) | If the Customer is interested for the Credit Card , 0 : Customer is not interested , 1 : Customer is interested |

## Evaluation Metric
The evaluation metrics for this competition is [ROC AUC Score](http://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html).

## Leaderboard
**Public Leaderboard:** : 

**Public LB Score:** 

**Private Leaderboard:** 

**Private LB Score:** 
