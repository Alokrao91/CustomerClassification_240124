


















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



modeling : 
1) we are going to start with the basic model and then optimize the model to get the best performance!!.
   
2) class 2 are low revenue customers and class 1 are high revenue customers.
 
3) we see that there exists a class imbalance.
 
4) class imbalance is a problem (90% are 2 and 10% are 1).


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
best values for Ensemble of classifiers like bestlr+bestrf+knn(best logistic regression,best random forest, KNeighborsClassifier)

 train F1 Score - 0.8803771361225692
 val F1 Score - 0.8212560386473431
 
BEST MODEL Prediction Is Support Vector Machines(svm)-SVC WITH TRAIN AND VALIDATION SCORE
MeanTrainScore -0.880569808285088
MeanTestScore - 0.850693137946377
