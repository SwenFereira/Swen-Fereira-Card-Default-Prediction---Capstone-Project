# Card-Default-Prediction---Capstone-Project

In today’s world, credit cards have become a lifeline to a lot of people. Now we know the most common issue there is in providing these kind of deals are people not being able to pay the bills. These people are what we call “defaulters”.

Credit card default happens when you have become severely delinquent on your credit card payments.Missing credit card payments once or twice does not count as a default. A payment default occurs when you fail to pay the Minimum Amount Due on the credit card for a few consecutive months.

Objective of our project is to predict which customer might default in upcoming months.The research aims at developing a mechanism to predict the credit card default beforehand and to identify the potential customer base that can be offered various credit instruments so as to invite minimum default.

•	This Dataset is from Taiwan. 

•	In our data set there are 30000 rows, 26 columns.

•	There are No Missing Values present .

•	There are No Duplicate values present.

•	There are No null values.

•	And finally we have 'default payment next month' variable which we need to predict for new observations.

•	9 Categorical variables present.

•	6 Months payment and bill data available.



•	Data categorical variables had minority classes which were added to their closest majority class

•	There were not huge gap but female clients tended to default the most.

•	Labels of the data were imbalanced and had a significant difference.

•	Gradient boost gave the highest accuracy of 82% on test dataset.

•	Repayment in the month of september tended to be the most important feature for our machine learning model.

•	The best accuracy is obtained for the Random forest and XGBoost classifier.


In general, all models have comparable accuracy. Nevertheless, because the classes are imbalanced (the proportion of non-default credit cards is higher than default) this metric is misleading.

Furthermore, accuracy does not consider the rate of false positives (non-default credits cards that were predicted as default) and false negatives (default credit cards that were incorrectly predicted as non-default).

Both cases have negative impact on the bank, since false positives leads to unsatisfied customers and false negatives leads to financial loss.

From above table we can see that XGBoost Classifier having Recall, F1-score, and ROC Score values equals 82%, 77%, and 86% and Random forest Classifier having Recall, F1-score, and ROC Score values equals 81%, 75%, and 84%.

XGBoost Classifier and Decision Tree Classifier are giving us the best Recall, F1-score, and ROC Score among other algorithms. We can conclude that these two algorithms are the best to predict whether the credit card is default or not default according to our analysis.
