# Heart Disease Prediction Using Machine Learning

## 📌 Project Overview
This project uses Machine Learning to predict whether a person has heart disease based on medical data. It applies classification algorithms to analyze patient information and make predictions.

## 🎯 Objectives
- Clean and preprocess the dataset.
- Perform Exploratory Data Analysis (EDA).
- Train and evaluate classification models.
- Compare model performance.
- Save and load the trained model using Joblib.

## 📊 Dataset
**Dataset:** Heart Disease UCI

The dataset contains medical attributes such as:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Exercise-Induced Angina

**Target column:** `num`

For this project, the target is converted into two classes:
- `0` — No heart disease
- `1` — Heart disease

## 🤖 Machine Learning Algorithms
- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## ⚙️ Project Workflow
1. Load the dataset.
2. Clean the data and handle missing values.
3. Perform exploratory data analysis.
4. Encode categorical features and scale numerical features where required.
5. Split the data into training and testing sets.
6. Train classification models.
7. Evaluate models using accuracy, precision, recall, confusion matrix, and ROC curve.
8. Apply cross-validation and GridSearchCV.
9. Save and load the trained model using Joblib.
10. Predict heart disease for new patient data.

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- Confusion Matrix
- ROC Curve and AUC


