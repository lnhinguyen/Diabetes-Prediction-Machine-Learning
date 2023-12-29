# Diabetes-Prediction-Machine-Learning
# Overview
In this project, I will build different Machine Learning models to predict diabetes among US residents. The data is retrieved from the National Health Interview Survey of the United States, containing 27,651 rows and 637 columns. This large dataset requires thorough investigation and preprocessing, which is described clearly in Preprocessing IPYNB file.

# Part 1: Preprocessing
In this part, I investigated the dataset and used both literature review and Python technique (SelectKBest) to extract the most relevant variables. The simplified dataset is then cleaned. 

# Part 2: Model Building
- First trial: In this step, I built 6 machine learning models (Logistic Regression, KNN, AdaBoost, Naive Bayes, Decision Tree, Random Forest) and compared the models using evaluation metrics
- SMOTE: After evaluating models in the first trial, statistics show that there is imbalance in the dataset (high accuracy, low F1). I used SMOTE to alleviate this problem
- Second trial: After SMOTE, I rerun the models with new data

# Results
Random Forest performed best among 6 models. The exercise also showed the importance of feature selection and SMOTE in classification using large-scale data.
