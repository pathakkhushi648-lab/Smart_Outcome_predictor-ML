# Smart_Outcome_predictor-ML

An end-to-end Machine Learning project that predicts student course completion and final academic scores using student engagement, learning activity, and performance data.The project applies data preprocessing, exploratory data analysis, feature engineering, and ensemble learning techniques to build predictive models for educational analytics.

---

## Project Overview

Educational institutions collect large amounts of student learning data, including attendance, quiz performance, learning sessions, assignments, and engagement activity.

This project uses Machine Learning to:

- Predict whether a student will complete a course.
- Predict the student's final academic score.
- Identify important factors influencing student outcomes.
- Compare multiple Machine Learning and Ensemble Learning models.

---

## Machine Learning Tasks

### 1. Classification

**Objective:** Predict course completion status.

**Target Variable:**

```text
completion_status
2. Regression

Objective: Predict the final academic score.

Target Variable:

final_score
Dataset
Property	Details
Domain	Educational Analytics
Records	Approximately 5,200
Features	19
Classification Target	completion_status
Regression Target	final_score
Important Features
age
country_region
device_type
education_background
course_level
course_category
sessions
time_spent_hours
videos_watched
quiz_attempts
assignments_submitted
forum_posts
avg_quiz_score
attendance_rate
Machine Learning Pipeline
Data Collection
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Missing Value Treatment
      ↓
Duplicate Removal
      ↓
Exploratory Data Analysis
      ↓
Covariance & Correlation Analysis
      ↓
Outlier Detection & Treatment
      ↓
Feature Engineering
      ↓
Categorical Encoding
      ↓
Feature Scaling
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Ensemble Learning
      ↓
Model Evaluation
      ↓
Model Comparison

Exploratory Data Analysis

The following analysis was performed:

Dataset structure and data types.
Descriptive statistics.
Missing value analysis.
Duplicate record analysis.
Numerical feature distributions.
Categorical feature distributions.
Outlier analysis.
Covariance analysis.
Correlation analysis.
Relationship between student engagement and final academic performance.
Data Preprocessing

The following preprocessing techniques were applied:

Missing value treatment.
Duplicate record removal.
Outlier detection using the IQR method.
Date feature extraction from course_start_date.
Categorical feature encoding.
Numerical feature scaling using StandardScaler.
Feature and target separation.
Train-test splitting.
Feature Engineering

The following features were extracted from course_start_date:

start_year
start_month
start_day
Machine Learning Models
Classification Models
Decision Tree Classifier
Bagging Classifier
AdaBoost Classifier
Gradient Boosting Classifier
LightGBM Classifier
XGBoost Classifier
Voting Classifier
Stacking Classifier
Regression Models
Decision Tree Regressor
Bagging Regressor
AdaBoost Regressor
Gradient Boosting Regressor
LightGBM Regressor
XGBoost Regressor
Voting Regressor
Stacking Regressor
Model Evaluation
Classification Metrics
Accuracy
Precision
Recall
F1-Score
ROC-AUC
Confusion Matrix
Regression Metrics
MAE
MSE
RMSE
R² Score
Model Performance
Classification Results

Key Insights
Student engagement and learning activity are important indicators of academic outcomes.
Attendance rate and average quiz score provide valuable information for predicting final performance.
Ensemble learning models performed better than a single Decision Tree model.
Boosting algorithms demonstrated strong performance on the structured tabular dataset.
Machine Learning can support early identification of students who may require additional academic assistance.
Business Applications

This project can support:

Early identification of at-risk students.
Course completion prediction.
Academic performance prediction.
Student retention analysis.
Personalized learning support.
Data-driven academic decision-making.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
LightGBM
Jupyter Notebook
Project Structure
Smart-Outcome-Predictor/

Future Improvements
Hyperparameter tuning using GridSearchCV and RandomizedSearchCV.
Cross-validation for more robust model evaluation.
Explainable AI using SHAP.
Streamlit deployment for real-time predictions.
Interactive Power BI dashboard.
Cloud deployment and API integration.

Author
Swarna Pathak
