# Titanic: Machine Learning From Disaster
* This is the Repository for Kaggle Competition, Titanic: Machine Learning From Disaster. 
https://www.kaggle.com/c/titanic/overview
* It is based on train and test dataset.
* We did Exploratory Data Analysis and Feature Engineering of survivals from different perspectives
* For our model building we used are Random Forest Classifier, Decision Tree Classifier, Support Vector Machine (SVM), K -Nearest Neighbors, Decision Tree, Gaussian Naive Bayes and Voting Classifier


## Resources We Used
* We used pandas, numpy, sklearn, matplotlib, seaborn packages.


## Data Cleaning and Exploratory Data Analysis
* We analyzed and cleaned this dataset so it can be usable for our model
* And in EDA part, we simplified our data and analyzed different value counts through graphs also through pivot table


## Model Building
* We transformed our variables into dummy variables
* We used different different Models to evaluate
* The Random Forest model performed better than the other approaches on the test set. 

Model Used| Score
------------ | -------------
Random Forest | 94.84%
Decision Tree	 | 94.84%
Voting Classifier	 | 88.66%
K -Nearest Neighbors	 | 87.32%
Logistic Regression	 | 84.62%
Support Vector Machine (SVM)	 | 76.21%
Gaussian Naive Bayes	 | 75.31%

