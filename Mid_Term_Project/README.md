# Malware prediction using RandomForest Classifier.

* Your IT department has been struggling with an onslaught of malware of different types for the past several months, painstakingly grouped into a few types. Now, one of their data centers has gone down, and they believe it's due to the same malware. But it takes weeks to sort out what kind they've been hit with. The CIO heard that you took DATA 602 and asked for your help. You've been given a dataset of the features the CERT has developed so far, and the associated malware family IDs.
* The CIO has the following goals for you:

1. Can you develop a classifier based on this data, and can it give us an accurate estimate of which malware family has just taken down our data center?
2. What can you tell the CIO about what has already been found and processed by the CERT? All of the feature creation and labeling is expensive!
Like many real-world projects, you've been thrown into this with no documentation or information about the data or its quality. You've met two people from the CERT doing this work. One was pretty sharp, and the other seemed like their dad must have gotten them the job... worse, the person who developed the features quit last week.

* For this exam, it is intentionally free-form. Simply building a model won't be sufficient. You need to have a report (i.e., this notebook!) for the CIO on what you've done, why you think it will work, the weaknesses & strengths of what you've done. This exam is intentionally vague and open-ended.
* You can download the exam csv here: https://www.dropbox.com/s/skrdvxl9xt58ucm/data602_exam.csv?dl=0. 


# Results

* Based on the results, the Random Forest Classifier stands out as the best-performing model with the highest accuracy of around 90.73% on the test data. It demonstrates good generalization ability and robustness to new, unseen data.

* The Decision Tree Classifier also performed well on the test data but might require pruning or depth limitation to avoid overfitting.

* The Logistic Regression model, Ridge Regression, and Lasso Regression showed varied performance, with the Logistic Regression model performing moderately, while Ridge and Lasso Regression models struggled to achieve high accuracy on the test data.

* To further improve the models, hyperparameter tuning, feature engineering, and cross-validation should be considered. Additionally, addressing potential data imbalances or data quality issues may lead to more reliable and accurate predictions.
