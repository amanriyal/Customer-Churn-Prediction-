# Customer-Churn-Prediction-
A comprehensive machine learning project built in Python to predict customer churn using data preprocessing, feature engineering, and tuned classification algorithms.
Customer churn is a critical metric for subscription-based services. This project uses a comprehensive customer dataset to build, evaluate, and optimize predictive models capable of identifying clients at high risk of leaving, allowing businesses to take proactive retention measures.

Key Features & WorkflowData
Preprocessing & Encoding: Handled categorical variables using Label Encoding for binary features and One-Hot Encoding (pd.get_dummies) for multi-class attributes like subscription tiers and contract lengths.   
Feature Scaling: Implemented StandardScaler ensuring proper separation by fitting exclusively on training data and transforming the test split to prevent data leakage.   
Model Training & Experimentation: Evaluated multiple machine learning algorithms including Logistic Regression, K-Nearest Neighbors (KNN), Gaussian Naive Bayes, and Decision Tree Classifiers.  
Regularization & Overfitting Control: Tuned hyperparameters (such as max_depth on the Decision Tree) to resolve overfitting, balancing training and test accuracies at an optimal $\sim 95.9\%$ performance level.
