The task is to predict whether the user will be able to successfully complete the online course "Data Analysis in R" on Stepik.org.
The result of checking the accuracy of predictions was the ROC AUC score.
<b> RandomForestClassifiar</b>  was used as an algorithm.

Predict the probability based on two days of user activity on the course, that they will score more than 40 points in the course

<b>What we have:</b> 

data/events_data_train.zip - training data about the target actions of users on the course

data/submission_data_train.zip - training data with task status (correct/incorrect)

data/events_data_test.zip - test data about the targeted actions of users on the course, with data for the first 2 days

data/submission_data_test.zip - test data with issue status (correct/incorrect), with data for the first 2 days


<b> Result:</b> 

A csv file is generated with an estimate of the probability of classes.
<b> ROC AUC score</b>  on test data is 0.89.
