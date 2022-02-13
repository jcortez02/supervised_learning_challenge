# supervised_learning_challenge

#Results

Overall the random forest model performed the best, however the model scored a 64%. The rest of models scored the following....
- Logistic Regression: 53%
- Logistic Regression (scaled): 55%
- Random Forest (scaled): 52%

The scores we received from our models is indicative that we can’t use 2019 loan risk level information to predict the risk level of 2020 loans.

#Predictions prior to modeling

I would think the random forest model would be better for this classification situation since you are dealing with types of groups (low & high risk) and not necessarily groups with numbers to be classified by. 

#Predictions prior to scaling the data

Typically scaled data will be more accurate because it will account for a data set that has features with varying degrees of data points (loan amounts, loan rates, etc). I thought the models would be a bit more accurate because of this and have a low degree of score discrepancy in comparison to each other (regression vs forest). However, the models were less accurate than the unscaled data. The scaled models were close when comparing scaled regression versus scaled random forest, but still too low to use in predicting 2020 loan risk levels.