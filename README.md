 Insurance Claim Prediction Project

 Project Overview
This project builds a machine learning model to predict whether a building will have at least one insurance claim during the insured period based on building characteristics.

Target Variable:
- Claim = 1: Building has at least one insurance claim
- Claim = 0: Building has no insurance claim

Objectives
- Perform data cleaning and preprocessing
- Conduct Exploratory Data Analysis (EDA)
- Train multiple machine learning models
- Evaluate and compare model performance
- Select the best performing model

Dataset
The dataset contains building-related features such as:
- Building dimension
- Date of occupancy
- Residential status
- Building painted
- Building fenced
- Garden
- Settlement
- Geo code
- Number of windows

Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Models Implemented
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC score

 Key Findings
- Tree-based models (Random Forest and Gradient Boosting) performed better than Logistic Regression.
- Building characteristics such as size and residential status influence claim probability.
- The model can assist insurance companies in risk assessment and decision-making.

Project Structure# insurance-claim-prediction-2
Machine learning project to predict insurance claims
Future Improvements
- Apply hyperparameter tuning
- Handle class imbalance using SMOTE
- Try advanced models such as XGBoost or LightGBM

Author
Gladys Gbise
