# 🌧️ Rainfall Prediction Using Machine Learning

This project presents a supervised machine learning approach to predict **whether it will rain tomorrow**, based on a variety of historical climatic conditions. The model is built on real-world weather data and demonstrates a complete data science pipeline, from preprocessing to evaluation.

---

## 📌 Problem Statement

Given past weather records (e.g., wind, humidity, temperature, rainfall yesterday), predict whether or not it will rain the next day. This is a **binary classification** problem (`Yes` or `No`).

---

## 📂 Dataset

- Historical weather dataset containing both **numerical** and **categorical** features.
- Key features include:
  - `Rainfall`, `WindSpeed`, `Humidity`, `Temperature`, `RainToday`, etc.
- Target variable: `RainTomorrow`

---

## ⚙️ Tools & Technologies

- **Language**: Python 3.x  
- **Libraries**:
  - `pandas`, `numpy` – data handling
  - `matplotlib`, `seaborn` – data visualization
  - `scikit-learn` – preprocessing, model building, evaluation
  - `xgboost` *(optional)* – gradient boosting classifier
- **Environment**: Jupyter Notebook / VSCode

---

## 🔄 Data Preprocessing

- Handled **missing values** using `SimpleImputer`
- Applied **one-hot encoding** to categorical features
- Standardized/normalized numerical features
- Feature selection and elimination of irrelevant columns

---

## 🧠 Model Building

- Multiple models trained: `Logistic Regression`, `Random Forest`, `XGBoost`
- Final model selected based on cross-validation and evaluation metrics
- Achieved:
  - **Accuracy**: 83%
  - **F1 Score**: 0.79
  - **Precision**: 0.81
  - **Recall**: 0.77
  - **ROC-AUC**: 0.85

---

## 📊 Model Evaluation

- Evaluation metrics used:
  - Confusion Matrix
  - Accuracy, Precision, Recall, F1-score
  - ROC Curve & AUC
- Visualized model performance and feature importance

---

## 📈 Results

The final model predicts rainfall with **83% accuracy**, demonstrating strong generalization on unseen weather conditions. The model is balanced in terms of precision and recall, making it suitable for real-world forecasting use cases.

---

## 🚀 Future Work

- Deploy model using **Flask** or **Streamlit**
- Automate pipeline using **MLflow** or **Airflow**
- Incorporate **time-series forecasting** techniques

---

