The task is to predict whether the user will be able to successfully complete the online course "Data Analysis in R" on Stepik.org. 
The result of checking the accuracy of predictions was the ROC AUC score. 
RandomForestClassifiar was used as an algorithm


What we have:
data/events_data_train.zip - training data about the target actions of users on the course
data/submission_data_train.zip - training data with task status (correct/incorrect)

data/events_data_test.zip - test data about the targeted actions of users on the course, with data for the first 2 days
data/submission_data_test.zip - test data with issue status (correct/incorrect), with data for the first 2 days
