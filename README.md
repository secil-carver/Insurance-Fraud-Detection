[![](https://img.shields.io/badge/Python-blue?style=for-the-badge)](https://github.com/hamzamohdzubair/redant)
[![](https://img.shields.io/badge/ML-Models-blueviolet?style=for-the-badge)](https://hamzamohdzubair.github.io/redant/)
[![](https://img.shields.io/badge/Library-Scikitlearn-yellow?style=for-the-badge)](https://docs.rs/crate/redant/latest)
[![](https://img.shields.io/badge/Library-Scipy-orange?style=for-the-badge)](https://crates.io/crates/redant)

![](https://img.shields.io/static/v1?label=&message=DataExploration&color=green)
![](https://img.shields.io/static/v1?label=&message=Predictions&color=blue)

# Car Insurance-Fraud-Detection
Detecting insurance fraud with machine learning models

## Research Question
Can fraudulent insurance claims be predicted using machine learning models?

## Goal of Analysis
By examining the relationship between claimants and other variables and utilizing a machine learning model, this study aims to create a functioning model to help an insurance company improve its fraud detection program. Once a functioning model is developed, it can be used as a starting point to investigate possible fraudulent claims further.

## Models Used
Logistic Regression: A statistical classification algorithm used for binary classifications into distinct categories using a maximum likelihood estimation formula to predict the log odds of the target variable, which can then be turned into probability. Though it is easy to interpret, it does assume linearity among the variables.

log[p(X) / (1-p(X))]  =  β0 + β1X1 + β2X2 + … + βpXp

p(X) = eβ0 + β1X1 + β2X2 + … + βpXp / (1 + eβ0 + β1X1 + β2X2 + … + βpXp)


KNearest Neighbor: Knn is a supervised machine learning algorithm that captures similarity based on calculations of the distance of two points on a plane and then makes classifications. Although it can be used for regression problems, knn is most suited for classification problems.

 ![image](https://github.com/secil-carver/Insurance-Fraud-Detection/assets/77639654/0244a838-7f0e-4fdf-834a-4869bf1205a4)


Decision Tree: The decision tree is a supervised machine algorithm with a tree-like model of decisions and their probable outcomes. A decision tree’s hierarchical tree structure consists of a root node, branches, internal nodes, and leaf nodes. The decision tree starts with the root node, based on the available features branching out to internal nodes, then ultimately to the leaf nodes, representing all the possible outcomes within the data. Decision trees can be used for classification or regression problems.
 
![image](https://github.com/secil-carver/Insurance-Fraud-Detection/assets/77639654/401a960c-b48f-441c-acf9-b0949cf2abde)


Random Forest: Random Forest is an ensemble method that can be used for classification and regression problems. It operates by constructing multiple decision trees on multiple subsets of data using averages for maximum accuracy while controlling the over-fitting. Random forest reduces overfitting by combining many weak learners that underfit.

![image](https://github.com/secil-carver/Insurance-Fraud-Detection/assets/77639654/f5578869-698f-4876-9fec-dd95eff76df5)


Gradient boosting: Gradient Boosting is an ensemble learning algorithm, similar to the random forest, that builds simpler or weaker prediction models sequentially, where each model tries to predict the error left over by the previous model to obtain a better model. Both random forest and gradient boosting build a model consisting of multiple decision trees. The difference between random forest and gradient boosting is how the trees are built. Gradient boosting has no assumptions and can handle non-linear and imbalanced data.  
Comparison of Random Forest and Gradient Boosting

 ![image](https://github.com/secil-carver/Insurance-Fraud-Detection/assets/77639654/92938edb-4bee-404a-8302-1017ac58d927)
