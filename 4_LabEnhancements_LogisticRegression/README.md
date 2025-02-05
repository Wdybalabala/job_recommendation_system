# 4_LabEnhancements_LogisticRegression

This lab enhancement was conducted by:

Student Name    : Cheryl Gwee En Xin

Student ID      : 1211103146

## Enhancements Done
The main enhancements done were rewording, clarifying, reformatting, and rearrranging parts to make the learning process of logistic regression more smooth. Main parts added were cross-validation for hyperparameter tuning, 

- Added an introductory section for logistic regression to explain the basic overview and provide real-world application examples. 

- Provided more detailed explanations on Logistic Sigmoid, Logistic Regression Model, Log-Odds (Logit) Function, and Decision Boundary, rearranging and rewording to clarify and explain concepts better

- Reword and clarify the Single-Predictor Binary Logistic Regression section
  - Provide explaination why linear regression is not suitable for data with non-linear relationships
  - Minor edits in explanation for metrics
  - In `Single-Predictor Binary Logistic Regression` > `Single-Predictor Binary Logistic Regression With scikit-learn: Example 1` > `Improve the Model` subsection, added cross-validation methods to expound upon the hyperparameter tuning of regularization (C value) in logistic regression. Also added a visual demonstrating the differences of different hyperparameters. Using k-fold and its variant LeaveOneOut cross validation, the best cross-validation C value is obtained. This method can be applied to other types of logistic regression as well.

- Reword and clarify the Multiple-Predictor Binary Logistic Regression section
  - Add a discussion section on hyperparameter tuning and the k-fold cross-validation method, clarifying how cross-validation works to balance the bias-variance tradeoff, the importance of selecting an optimal C hyperparameter, and why a model with high accuracy does not mean a good model but rather shows the risk of overfitting.
  - Add a section to try different datasets with different characteristics (high noise, clearer patterns, high dimensionality), and how it affects the selection of the regularization strength by cross-validation.
  - Add 3D visualization for OVR method 

- Add explanation on multiclass logistic regression
  - Add explanation on OVR and Softmax approaches
  - Add a text section to discuss the differences of the two approaches

- Add 3d visualizations for each class in OVR and Softmax models 


## Lab Table of Contents

>Lab08 - Logistic Regression

>Import Libraries

>Logistic Regression

>The Logistic Sigmoid Function

>Visualization of Exponentials and the Sigmoid Function

>The Logistic Regression Model

>The Log-Odds (Logit) Function, Logistic Regression Function & Decision Boundary

>>The Log-Odds (Logit) Function

>>The Decision Boundary

>Types of Logistic Regression

>>Binary Logistic Regression

>>Multiclass/Multinomial Logistic Regression

>>Single-Predictor/Univariate Logistic Regression

>>Multiple/Multivariate Logistic Regression

>>Key Takeaways

>Single-Predictor Binary Logistic Regression

>>>Creating and Fitting Single-Predictor Binary Logistic Regression

>>Single-Predictor Binary Logistic Regression With scikit-learn: Example 1

>>>Linear Regression Not Suitable Tool

>>>Create and Fitting the Logistic Regression Model Using scikit-learn

>>>Confusion Matrix, Precision, Recall & $F_1$- Score

>>>Predict New Data Points

>>>Improve the Model

>>Binary Logistic Regression With scikit-learn: Example 2

>Multiple-Predictor Binary Logistic Regression

>>>Create and Fitting Multiple-Predictor Binary Logistic Regression

>>>Create and Fitting the Logistic Regression Model Using scikit-learn

>>>Understanding Bias-Variance Tradeoff in Cross-Validation for Hyperparameter Tuning (A continuation of the discussion in "Improve the Model" subsection)

>>>>Why cross-validation chooses C=0.001 as the best hyperparameter, even though the C=30 model returns higher accuracy

>>>>Predict New Data Points

>>>>TODO: Trying Different Datasets and How It Affects the Selection of C

>Multiclass Logistic Regression

>>>Create and Fitting Multiple-Predictor Binary Logistic Regression

>>One-Vs-Rest (OVR) Approach for Computing Prediction

>>Softmax Approach for Computing Prediction

>>Differences between the Two Approaches

>One-Vs-Rest (OVR) Approach

>>>Create and Fitting the Logistic Regression Model Using scikit-learn

>>Predict New Data Points

>>TO DO: Let's Experiment!

>Multinomial Approach Using Softmax

>>>Create and Fitting the Logistic Regression Model Using scikit-learn

>>TO DO: Let's Experiment!

>Real World Logistic Regression Application: Handwriting Recognition

>Real World Logistic Regression Application: Diabetes Prediction

>Mount Google Drive

>Logistic Regression With StatsModels: Example
