# Quality-of-Life-Prediction-using-Machine-Learning
This project aims to predict the Quality of Life (QoL) among Asian Americans using machine learning (ML). By leveraging survey data, the goal was to identify the key factors influencing QoL and build robust predictive models to classify individuals into high, moderate, or low QoL categories.

Techniques Used:
Data Preprocessing:

Handling Missing Values:
Rows with entirely missing data and those lacking QoL responses were removed.
Categorical variables were imputed using mode, and numerical ones using mean or median based on data distribution.
Feature Engineering:
Combined related variables to form new composite variables (e.g., Awareness of Services, Civic Engagement).
Dropped irrelevant features and encoded categorical data using label and ordinal encoding.
Multicollinearity Check:
Applied Pearson correlation for numerical variables and Cramér's V for categorical ones, identifying and addressing highly correlated features.
Model Development:

Machine Learning Models:
Implemented various classifiers, including Logistic Regression, Decision Trees, Support Vector Machines (SVM), Random Forest, XGBoost, K-Nearest Neighbors (KNN), Naive Bayes, and ensemble methods like Stacking Classifier.
Class Imbalance Management:
Addressed the significant class imbalance using SMOTE (Synthetic Minority Oversampling Technique) and oversampling.
Evaluation Metrics:
Models were assessed using Accuracy, Precision, Recall, and F1 Score.
Hyperparameter Tuning:

Applied tuning on the original, SMOTE-balanced, and oversampled datasets to optimize performance.
Clustering Analysis:

Techniques like K-Prototypes, K-Medoids, and KMeans were applied but showed low silhouette scores, indicating poor cluster separation.
Key Results:
Top Model: The Stacking Classifier outperformed other models with a 75% accuracy after hyperparameter tuning, demonstrating superior performance in predicting QoL.

Important Factors: Significant predictors of QoL included:

Health status
Financial stability
Civic engagement
Class Imbalance Handling: SMOTE and oversampling effectively balanced the dataset, enhancing the model's ability to predict underrepresented QoL categories.

Conclusion:
This project successfully leveraged machine learning to predict QoL among Asian Americans, identifying crucial influencing factors. The Stacking Classifier emerged as the most effective model, highlighting the power of ensemble techniques for handling complex and imbalanced datasets. These findings offer valuable insights for policymakers and community leaders to improve the QoL in targeted areas.

# Link for the Presentation

https://www.canva.com/design/DAGUHpJkN54/k7hm7JoxydJWJKM1_b1FFg/edit

# Link for the Report

https://drive.google.com/drive/folders/1fLPhS_xeY7JwRQipAr-7RAgKg_dpNmZz?usp=sharing

