# TitanicAnalysis
The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

## Goal :
Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

## Dataset :

Titanic dataset(4 categorical variables). There are 891 rows and 12 columns in this dataset.
This dataset is imbalanced dataset where we need to predict two classes "Yes" or "No". In the dataset, there are less than 80% Majority class, so, I decided to go with accuracy as evaluation metric.

**Models Used**

* KNN classification
* Logistic Regression 
* Linear Support Vector Machine 
* Kernelized Support Vector Machine (rbf, polynomial and sigmoid kernels)
* Decision Tree classification
* Two models with Bagging
* Two models with Pasting 
* Random Forest, Ada Boost (with decision tree) 
* Gradient Boost
* Extra-Trees
* XGBoost
* Voting Classifier to combine results of top 5 models
* Voting Classifier to combine results of models with least correlation
* Stacking Classifier to combine results of top 5 models
* Stacking Classifier to combine results of models with least correlation
