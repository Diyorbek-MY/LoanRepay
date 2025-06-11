link in kaggle: https://www.kaggle.com/competitions/binaryclassificationwithabankchurndataset/

# 💳 Bank Customer Repayment Prediction

This project focuses on predicting whether a customer will **repay a loan** or not based on their financial and demographic information. It is part of a certification project that demonstrates skills in data preprocessing, model development, and evaluation using supervised machine learning techniques.

---

## 📂 Dataset

The dataset used in this project is from a bank churn prediction problem and includes:

- `train.csv` – training data with features and labels.
- `test.csv` – test data for prediction submission.
- `sample_submission.csv` – format example for final predictions.

---

## 📊 Project Workflow

### 1. **Exploratory Data Analysis (EDA)**
- Analyzed missing values and distributions.
- Visualized target imbalance.
- Examined feature correlations.

### 2. **Data Preprocessing**
- Scaled numerical features.
- Encoded categorical variables using `OneHotEncoder`.
- Split data into train/validation sets.
- Built a full machine learning pipeline.

### 3. **Model Building**
Trained and evaluated multiple models:
- ✅ **Logistic Regression**
- ✅ **Random Forest Classifier**
- ✅ **LightGBM (LGBMClassifier)**

### 4. **Evaluation Metrics**
- Accuracy
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## 📈 Results

- **Best model**: `Random Forest` / `LightGBM` with highest ROC-AUC.
- **Top features** influencing repayment: `CreditScore`, `Age`, `Balance`.

---

## 📁 Folder Structure

