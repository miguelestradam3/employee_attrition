# 👥 Employee Attrition Prediction using Machine Learning

This project demonstrates how to build machine learning models to predict **employee attrition** using human resources (HR) data. The notebook walks through the complete machine learning pipeline, including data exploration, preprocessing, feature engineering, handling class imbalance with **SMOTE**, model training, and performance evaluation.

The primary objective is to identify employees who are at risk of leaving an organization, enabling data-driven retention strategies.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Employee attrition visualization
- Data cleaning and preprocessing
- Label Encoding
- One-Hot Encoding
- Feature scaling using MinMaxScaler
- Handling class imbalance with SMOTE
- Train/Test split
- Logistic Regression model
- XGBoost classifier
- Model performance evaluation
- Correlation heatmaps and feature analysis

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
imbalanced-learn
jupyterthemes
```
---

## 📊 Dataset

The project uses an **HR Analytics Employee Attrition** dataset containing employee demographic, professional, and performance information.

Example features include:

- Age
- Department
- Job Role
- Education
- Monthly Income
- Business Travel
- Job Satisfaction
- Environment Satisfaction
- Work-Life Balance
- Years at Company
- Total Working Years
- Overtime
- Stock Option Level
- Distance From Home

### Target Variable

- **Attrition**
  - Yes
  - No

The goal is to predict whether an employee is likely to leave the company.

---

## 🔍 Exploratory Data Analysis

The notebook performs extensive exploratory analysis, including:

- Dataset inspection
- Missing value verification
- Employee attrition distribution
- Correlation heatmaps
- Histograms
- Count plots
- Distribution plots
- Feature relationship analysis

These visualizations help identify the factors that influence employee turnover.

---

## ⚙️ Data Preprocessing

Several preprocessing techniques are applied before model training:

- Label Encoding for binary categorical variables
- One-Hot Encoding for multi-class categorical features
- Feature scaling using **MinMaxScaler**
- Train/Test split
- Class balancing using **SMOTE**

These steps prepare the data for effective machine learning.

---

## 🤖 Machine Learning Models

The notebook trains and evaluates multiple classification models, including:

- **Logistic Regression**
- **XGBoost Classifier**

The models are compared based on their predictive performance.

---

## 📈 Model Evaluation

The trained models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

These metrics provide a comprehensive assessment of each model's ability to predict employee attrition.

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/employee-attrition-prediction.git

cd employee-attrition-prediction
```

---

### Install dependencies

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn jupyterthemes
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the jupyter notebook

Run the notebook cells sequentially to reproduce the complete machine learning workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Explore HR analytics datasets
- Visualize employee behavior and attrition trends
- Encode categorical variables
- Scale numerical features
- Handle imbalanced datasets using SMOTE
- Train Logistic Regression and XGBoost models
- Compare classification performance
- Apply machine learning techniques to employee retention analysis

---

## 🔮 Future Improvements

- Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Compare additional models such as Random Forest, LightGBM, and CatBoost
- Perform feature importance analysis
- Generate ROC and Precision-Recall curves
- Implement cross-validation
- Deploy the model using Streamlit for interactive predictions
