# ElevateLabs_Task4
Implementing Logistic Regression as part of internship by Elevate Labs
Logistic Regression - Binary Classification Workflow

It demonstrates how to apply Logistic Regression for binary classification using Python and scikit-learn.

Steps Covered
Load Breast Cancer dataset

Train/Test Split & Standardization

Split data into training and testing sets.

Standardize features using StandardScaler.

Fit Logistic Regression

Train a logistic regression classifier with LogisticRegression.

Evaluation

Confusion Matrix

Precision, Recall, F1-score

ROC Curve & AUC

Threshold Tuning & Sigmoid

Logistic regression outputs probabilities using the sigmoid function:

𝜎(𝑧) =  1/(1+𝑒^−𝑧)​

Default threshold = 0.5, can be adjusted (e.g., 0.3, 0.7) depending on whether higher recall or higher precision is required.
