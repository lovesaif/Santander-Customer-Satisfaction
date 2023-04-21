# Santander-Customer-Satisfaction
Short Summary: In this project, there are hundreds of anonymized features to predict if a customer is satisfied or dissatisfied with their banking experience. So, here build a base model with Logistic Regression and further used Random Forest Classifier and XGBoost Classifier to predict the probability of each customer in the test set being unsatisfied.


# Dataset and Key Features: 
Here we used "Santander Customer Satisfaction" dataset easily available on Kagle.
1. Here the dataset has anonymous
column with numeric data
2. Data set contains many unnamed
columns
3. Unnamed columns make feature
extraction tedious
4.Here anonymized dataset containing a
large number of numeric variables. The
"TARGET" column is the variable to predict. It
equals one for unsatisfied customers and 0 for
satisfied customers. The task is to predict the
probability that each customer in the test set is an
unsatisfied customer
5. Exploratory data analysis on the
training set can reveal latent features
which contribute to the Target column.

# Model Used: 

1 Build a machine learning algorithm using the
training data set and predict the total satisfied and
unsatisfied customers in the Santander test data.

2.For initial set of experiment started with Logistic
Regression as a base model.

3.Here “Random Forrest” and “XG Boost” is used to
build a machine learning model.

# Conclusion:
Accuracy score is not the best score to
evaluate the performance of a
model.
For imbalanced dataset ROC-AUC
score and F1 score are better metrics
to evaluate the model.
From these metrics, it shows that
XGBoost Classifier is the best model
followed by Random Forest and
Logistic Regression trained on the
Santander Dataset.
