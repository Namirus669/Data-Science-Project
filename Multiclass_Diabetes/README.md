🩺 Multiclass Diabetes Classification using Machine Learning

This project focuses on building and evaluating machine learning models to classify individuals into three diabetes-related categories:
Non-Diabetic, Prediabetic, and Diabetic — using an imbalanced, multiclass dataset.

📘 Project Overview

The aim of this project is to explore how machine learning can be applied to detect potential diabetes conditions based on health-related features.
Various models are compared to find the most robust one, considering both imbalanced data and multi-class classification challenges.

⚙️ Methods and Workflow

Data Preprocessing

Handling missing values

Feature scaling

Splitting dataset into train–test sets

Exploratory Data Analysis (EDA)

Visualization of feature distributions

Relationship between features and diabetes classes

Detection of class imbalance

Model Building

Logistic Regression

Random Forest

Gradient Boosting

Model Evaluation

Metrics used: Precision, Recall, F1-score (Macro), and ROC-AUC (OvR)

5-Fold Cross Validation using Macro F1-score

📊 Results Summary
Model	Macro Recall	Macro F1	Macro ROC-AUC
Logistic Regression	0.896	0.859	0.953
Random Forest	0.950	0.936	0.985
Gradient Boosting	0.950	0.936	0.965

✅ Best Model: Random Forest
✅ Cross-Validation Mean F1 (Macro): Consistent with test set — showing strong model stability.

💡 Key Insights

Macro F1-score is more suitable than accuracy for imbalanced multiclass data.

Random Forest provides the best balance between precision and recall across all classes.

ROC-AUC > 0.95 indicates strong discrimination between all three diabetes categories.

Future improvements can include SMOTE, feature selection, and interpretability analysis (e.g., SHAP).