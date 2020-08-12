Fraud detection-Kaggle Competition
==================================
In `this competition<https://www.kaggle.com/c/data-science-circle-challenge/overview>_` we are predicting the probability that an online transaction is fraudulent, as denoted by the binary target isFraud.
The competition score was based on roc-auc score


The data contains:
-----------------
-TransactionDT:  timedelta from a given reference datetime (not an actual timestamp)
-TransactionAMT : transaction payment amount in USD
-ProductCD : product code, the product for each transaction
-card1 : card6 -payment card information, such as card type, card category, issue bank, country, etc
-addr : adress
-dist: distance
-P_ and (R__) emaildomain : purchaser and recipient email domain
-C1-C14 : counting, such as how many addresses are found to be associated with the payment card, etc. The actual meaning is masked.
-D1-D15 : timedelta, such as days between previous transaction, etc
-M1-M9 : match, such as names on card and address, etc.
-Vxxx : Vesta engineered rich features, including ranking, counting, and other entity relations.

The used libiraries:
--------------------
1- `Pandas<https://pandas.pydata.org/docs/>_`
2- `Numpy<https://numpy.org/doc/>_` 
3- `Sklearn<https://scikit-learn.org/stable/>_`


This notebook is training on using different techniques to get the highest score (got about 82%)



