![image alt](https://github.com/Alokrao91/CustomerClassification_240124/blob/main/customer%20classification.jpg?raw=true)










![image alt](https://github.com/Alokrao91/CustomerClassification_240124/blob/main/revenue-from-existing-customers.jpg?raw=true)


















# CustomerClassification_240124
A Capstone project


Customer Classification – Capstone Project
Objective
The goal of this project is to classify customers of a stock broking firm into two categories:

Class 1: High Revenue Customers

Class 2: Low Revenue Customers

By analyzing customer data, we aim to predict which customers are likely to generate high revenue, enabling the firm to focus its marketing and service efforts more effectively.

This is a supervised classification problem based on labeled historical data.

# Machine Learning Pipeline
The following steps were used to build the predictive model:

1)Data Loading
Imported the customer dataset into Python for processing.

2)Data Splitting
Split the dataset into training and validation sets (if a separate validation set is not provided).

3)Exploratory Data Analysis (EDA) & Preprocessing
Explored distributions, identified patterns, handled missing values, and normalized/encoded features.

4)Model Building
Implemented multiple classification algorithms, starting from basic models and moving toward more complex ones.

5)Model Evaluation
Evaluated using F1-score, accuracy, precision, and recall due to class imbalance.

6)Model Optimization
Tuned hyperparameters and experimented with ensemble models to improve performance.

# Challenge: Class Imbalance
There is a significant imbalance in the target classes:

90% of customers are Class 2 (Low Revenue)

10% of customers are Class 1 (High Revenue)

Class imbalance was addressed during model selection and evaluation using metrics like F1-score, which accounts for imbalanced classes.

# Algorithms Used
Several machine learning algorithms were implemented:

1)Logistic Regression

2)Random Forest

3)K-Nearest Neighbors (KNN)

4)Decision Tree

5)Support Vector Machine (SVM)

6)Gradient Boosting Classifier

# Hyperparameter Tuning
Two tuning strategies were applied to improve model performance:

1)GridSearchCV – Exhaustive search over parameter grid

2)RandomizedSearchCV – Random search over parameters for quicker results

 # Ensemble Model
An ensemble classifier was created by combining the best versions of:

1)Logistic Regression

2)Random Forest

3)KNeighborsClassifier

This hybrid approach yielded strong performance across training and validation sets.

# Performance Metrics
. Train F1 Score: 0.880

. Validation F1 Score: 0.821

The best performing model was Support Vector Machine (SVC), achieving:

. Mean Train Score: 0.881

. Mean Validation Score: 0.851
