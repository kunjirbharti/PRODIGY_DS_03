# PRODIGY_DS_03
# Objective
- Predict whether a customer will purchase a product or service (subscribe to a term deposit) based on their demographic and behavioral data.
# Dataset 
- Source : Bank Marketing Dataset - UCI Machine Learning Repository.
- Description : Contains data related to direct marketing campaigns (phone calls) of a Portuguese banking institution.
- Features : Includes attributes such as age, job, marital status, education, contact type, previous campaign outcomes, and more.
# Algorithm: Decision Tree Classifier (using Scikit-learn)
- Reason for Choice :
  Easy to interpret and visualize.
  Handles both categorical and numerical data.
  Effective for initial exploratory analysis.
 - Workflow :
Data Loading & Preprocessing (handling missing values, encoding categorical features, feature scaling).
Exploratory Data Analysis (EDA) and feature selection.
Training a Decision Tree Classifier.
Model Evaluation using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
Hyperparameter tuning using GridSearchCV.
Visualization of the decision tree structure.
- Evaluation :
Confusion matrix and classification report.
Visualization of decision boundaries and tree depth.
Comparison with baseline models (optional).
# Tools & Libraries
- Python (Jupyter Notebook or script)
- Pandas, NumPy for data manipulation
- Scikit-learn for modeling and evaluation
- Matplotlib, Seaborn for visualization
