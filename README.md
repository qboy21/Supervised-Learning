# Supervised-Learning
Analysis of LendingClub Loans

Goal

Improve the gross margin of LendingClub through the identification of problematic loans at the time of issuance for further analysis and/or allocation to securitization facilities.

Objective

Develop a supervised learning model that can effectively predict whether a loan will be fully paid off or charged off at the time of loan approval.


Summary

Based on the precision and recall scores of the model, we are able to match the current weighted average charge off rate on LendingClub's loans of 8.20%.

This lends credence to the company using a similar proprietary scoring model based on the features used in this project.
Gradient Boosting and eXtreme Gradient Boosting Train CV Score, Test Accuracy Score, and Test Fbeta score favoring recall were identical and either can be used for future development.


Next Steps

Lending Club has done a great job at optimizing their business model through the migration of loans from 60 month to 36 months. This has decreased the default rates, the duration of their investment portfolio to 16 months as well increased the issuance of loans on their marketplace.

Future development will now focus on external factors incorporated into the existing dataset and tailoring the ability to predict charge offs based on more select subsample criteria.

External data such as consumer credit change, demographic data, unemployment data, word analysis of the Federal Reserve forward guidance, and retails sales for a better view on lending as that is the key driver to the business.
