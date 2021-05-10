## Coursera Course: Machine learning with Python

In this Coursera project, I completed a notebook in which I built a classifier to predict whether a loan case will be paid off or not. 

A historical dataset from previous loan applications was loaded, the data was cleaned, and applied different classification algorithms. 
Used the following algorithms to build the models:

    k-Nearest Neighbour
    Decision Tree
    Support Vector Machine
    Logistic Regression

The results are reported as the accuracy for each classifier, using the following metrics when these are applicable:

    Jaccard index
    F1-score
    LogLoss

## Report

The accuracy of the built models using different evaluation metrics is shown in the table below:

| Algorithm          | Jaccard | F1-score | LogLoss |
| ------------------ | ------- | -------- | ------- |
| KNN                | 0.5575  | 0.6704   | NA      |
| Decision Tree      | 0.5645  | 0.7037   | NA      |
| SVM                | 0.5737  | 0.6831   | NA      |
| LogisticRegression | 0.5775  | 0.6717   | 0.5563  |

Note: The best K for the KNN model had a value of 7.

Please also note that the models might be improved by implementing additional feature engineering and feature selection techniques. Also, the models might also be improved by performing a Grid Search technique on the hyperparameters for each model. However, the purpose of the exercise in the limited implementation time was to apply some of the classification algorithms covered during the mentioned class in Coursera.
