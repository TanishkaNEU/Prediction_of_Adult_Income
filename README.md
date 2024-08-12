
# Prediction_of_Adult_Income

**Project Overview** 

Prediction of Adult Income
Welcome to the Prediction of Adult Income project! This project focuses on predicting whether an individual's annual income exceeds $50K using various machine learning techniques. By analyzing census data, we aim to uncover patterns and insights that can help in understanding the factors influencing income levels.

**Problem Setting & Definition**

Low income levels have raised concerns globally, leading us to investigate the factors that influence an individual's income. Our objective is to classify whether an adult's income is greater than or less than $50K based on attributes such as age, education, occupation, and more.

**Data Mining Techniques**

To achieve our goal, we utilized the following data mining tasks:

Data Cleaning & Exploration: Ensuring data quality by handling missing values and exploring data distributions.
Correlation Analysis: Evaluating relationships between different variables.
Principal Component Analysis (PCA): Simplifying data complexity while retaining essential patterns.
Statistical Analysis: Conducting Chi-Square tests and other statistical methods.

**Models Used**

We evaluated various classification models to identify the most effective one:

Logistic Regression: A simple yet effective baseline model.
Naive Bayes: Leveraged for its efficiency with categorical data.
K-Nearest Neighbors (KNN): Used for its simplicity and interpretability.
Support Vector Machine (SVM): The best-performing model, offering high accuracy and robust generalization.
After thorough testing and evaluation, Support Vector Machine (SVM) emerged as the top performer with an accuracy of 85% and a strong Area Under Curve (AUC) score, making it our recommended model for this dataset.

**Model Evaluation**

The models were evaluated based on accuracy, precision, recall, F1-score, and AUC. SVM emerged as the top-performing model with:
Accuracy: 85%
Precision: High precision, indicating a low false positive rate.
AUC: Strong area under the curve, suggesting a good balance between true positives and false positives.

**Conclusion**

Our analysis concludes that SVM provides the best classification performance for this dataset. This model effectively handles high-dimensional data and offers scalability, making it an ideal choice for predicting income levels.
