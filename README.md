# Udacity-Capstone-Project-Sparkify_PredictUserChurn
# Project Overview:
* This is a Udacity nanodegree project (Data Science Capstone). This project uses users’ event data from Sparkify to build a model to predict users’ churn.
* The original dataset is 12GB but a small subset of the dataset (128MB) will be used in this notebook.

# Methodology
* Define Target Variable (churn) and Exploratory Analysis
* Feature Engineering (Create New Feature and Transformation)
* Modeling (Random forest, logistic regression, SVM and gradient boosting tree)
* Evaluation (precision, recall, F1-score)


# Result

* We have taken 70/30 ratio to split the data into train and test set. After applying the machine learning algorithm we are getting f1 scores below
* logistic regression (best f1 score 0.73)
* gradient boosted tree (best f1 score 0.72 )
* Random Forest (best f1 score 0.7181)

we decided to choose logistic regression model because it is the best f1 score
