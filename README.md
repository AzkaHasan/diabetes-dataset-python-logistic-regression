# diabetes-dataset-python-logistic-regression
Logistic Regression on Diabetes Dataset
📌 Project Overview

This project explores Logistic Regression applied to the Diabetes dataset, using both R and Python.
The purpose is to compare results and learn how different tools handle the same statistical analysis.

🔹 Why R and Python?

R is widely used for statistics and academic analysis, providing rich summaries and visualization tools.

Python is preferred for machine learning and automation, with libraries like scikit-learn for quick modeling and evaluation.

By running the same analysis in both, we ensure consistency and better understanding of the data.

🔹 Steps Performed
1. Data Preparation

Converted the target variable into binary form using the median split.

Split dataset into 80% training and 20% testing.

2. Logistic Regression Model

Built a logistic regression model to predict the probability of diabetes (target = 1).

Generated predictions and classification results.

3. Evaluation

Calculated accuracy of the model.

Checked coefficients to see which features (e.g., BMI, Glucose) influence diabetes risk.

Visualized results with scatter plots, logistic regression curve, and confusion matrix.

🔹 Results
R Output

Logistic regression summary showed BMI and Glucose as strong predictors.

Accuracy ≈ similar to Python (around ~75% depending on split).

Visualization (pair plots & regression output) confirmed positive relationship between BMI and diabetes risk.

Python Output

Logistic regression with scikit-learn produced almost the same coefficients and accuracy as R.

Additional metrics: MSE, R², confusion matrix, classification report.

Visualization made the logistic S-curve clearer, showing how higher BMI increases diabetes probability.

🔹 Conclusion

Both R and Python give consistent results for logistic regression on this dataset.

BMI and Glucose are strong predictors of diabetes risk.

Logistic regression is a suitable method for binary classification when interpretability and feature importance are important.

R is better for detailed statistical interpretation, while Python is better for automation, scalability, and machine learning workflows.
