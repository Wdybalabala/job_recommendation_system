# 4_LabEnhancements_LogisticRegression

This lab enhancement was conducted by:
Student Name    : Cheryl Gwee En Xin
Student ID      : 1211103146

## Table of Contents

TODO: Insert table of contents


## Enhancements Done
Added an introductory section for logistic regression to explain the basic overview and provide real-world application examples. 

Provided more detailed explanations on Logistic Sigmoid, Logistic Regression Model, Log-Odds (Logit) Function, and Decision Boundary, rearranging and rewording to clarify and explain concepts better

Reword and clarify the Single-Predictor Binary Logistic Regression section
- Provide explaination why linear regression is not suitable for data with non-linear relationships
- Minor edits in explanation for metrics
- In `Single-Predictor Binary Logistic Regression` > `Single-Predictor Binary Logistic Regression With scikit-learn: Example 1` > `Improve the Model` subsection, added cross-validation methods to expound upon the hyperparameter tuning of regularization (C value) in logistic regression. Also added a visual demonstrating the differences of different hyperparameters. Using k-fold and its variant LeaveOneOut cross validation, the best cross-validation C value is obtained. This method can be applied to other types of logistic regression as well.

Reword and clarify the Single-Predictor Binary Logistic Regression section
- Add a discussion section on hyperparameter tuning and the k-fold cross-validation method, clarifying how cross-validation works to balance the bias-variance tradeoff, the importance of selecting an optimal C hyperparameter, and why a model with high accuracy does not mean a good model but rather shows the risk of overfitting.
