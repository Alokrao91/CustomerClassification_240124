# CustomerClassification_240124
A Capstone project

We are going to solve a customer classification Problem. The problem can be summarized as below:
1) Given the details about the customer our objective is to identify which customers is a potential high revenue customers and which customers are low revenue customers for a stock brocking firm.
2) The problem is a supervised classification problem.

Machine Learning Pipleline:

1) Load the Data into python.
2) Split the data into train and val (only when validation set is not provided separately).
3) Exploratory Data Analysis and Preprocessing.
4) Model Building.
5) Model Evaluation.
6) Iter over to improve the performance.


ML algorithms used:
1) logistic regression
2) random forest
3) KNeihborsClassifier
4) DecisionTreeClassifier
5) SVM
6) GradientBoostingClassifier


Hyperparameter Tuning:

1)GridSearchCV

2)RandomizedSearchCV

Created Own Ensemble of classfiers useing different algorithms.
BEST MODEL Prediction Is Support Vector Machines(svm)-SVC WITH TRAIN AND VALIDATION SCORE
MeanTrainScore -0.880569808285088
MeanTestScore - 0.850693137946377
