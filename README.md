# Bankruptcy-project-
# Overview
This project investigates the application of various machine learning models to predict bankruptcy, which is crucial for financial risk management. Using a dataset of financial attributes from numerous firms, models like Multivariate Discriminant Analysis (MDA), Logistic Regression (LR), GBM Classifier, and Naïve Bayes are employed to identify potential bankruptcies.
# Dataset
The dataset consists of 92,872 entries with 13 attributes, primarily skewed towards non-bankrupt instances. Attributes include financial metrics like EPS, Liquidity, and Profitability. The data has been cleaned and preprocessed to handle missing values and outliers, ensuring robust model training.
# Model Used
- Random Forest Classifier : A random forest classifier is a supervised learning algorithm that combines multiple decision trees to improve predictive accuracy and control over-fitting.
- XG Boost Classifier : An XGBoost classifier is a powerful machine learning algorithm that uses gradient boosting to create an ensemble of decision trees, known for its efficiency, speed, and high predictive accuracy.
# Model Performance 
The models' performances were evaluated based on precision, recall, F1-score, and overall accuracy:
- Random Forest Classifier
    - Initial model: High precision for non-bankrupt (1.00), low for bankrupt (0.14). Recall: 0.99 (non-bankrupt), 0.33 (bankrupt). F1-scores: 0.99 (non-bankrupt), 0.20 (bankrupt). Overall accuracy: 98%.
    - Tuned model: Precision for bankrupt dropped to 0.04, recall improved to 0.81. F1-scores: 0.93 (non-bankrupt), 0.07 (bankrupt). Overall accuracy: 86%.

- XG Boost Classifier
    - Initial model: Precision: 1.00 (non-bankrupt), 0.14 (bankrupt). Recall: 0.99 (non-bankrupt), 0.36 (bankrupt). F1-scores: 0.99 (non-bankrupt), 0.20 (bankrupt). Overall accuracy: 98%.
