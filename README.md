# 🏭 Machine Quality Prediction

## 📌 Project Overview

This project predicts the quality of manufactured products using Machine Learning techniques. It uses Random Forest Classification and Regression models to analyze manufacturing data and predict product quality and defect status.

The project demonstrates a complete machine learning workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and visualization.

---

## 📂 Project Structure

```
machine-quality-prediction
│
├── dataset/
│   └── smart_factory_synthetic_dataset_5000.csv
│
├── images/
│
├── notebook/
│   └── machine_quality_prediction.ipynb
│
├── .gitignore
└── README.md
```

---

## 🚀 Features

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Random Forest Classification
- Random Forest Regression
- Model Evaluation
- Data Visualization

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset

The project uses a synthetic smart factory manufacturing dataset containing production parameters and product quality information.

Example features include:

- Temperature
- Pressure
- Humidity
- Machine Speed
- Vibration
- Defect Status
- Quality Score

---

## 📈 Machine Learning Models

### Classification Model

- Algorithm: Random Forest Classifier

| Metric | Value |
|---------|------:|
| Accuracy | **93.7%** |
| Precision (Weighted Avg) | **0.96** |
| Recall (Weighted Avg) | **0.94** |
| F1-Score (Weighted Avg) | **0.95** |

### Regression Model

- Algorithm: Random Forest Regressor

| Metric | Value |
|---------|------:|
| R² Score | **0.902** |
| MAE | **8.43** |
| MSE | **115.10** |
| RMSE | **10.73** |

## 📷 Visualizations

### Correlation Heatmap

![Correlation Heatmap](images/corr.png)

---

### Classification Feature Importance

![Classification Feature Importance](images/cls_feature_imp.png)

---

### Regression Feature Importance

![Regression Feature Importance](images/reg_feature_imp.png)

---

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

### Workload vs Power Usage

![Workload vs Power Usage](images/power_vs_work.png)

---

### Material Type vs Defect Status

![Material Type vs Defect Status](images/Material%20type%20vs%20Defect%20status.png)

---

### Material Type and Humidity vs Defect Status

![Material Type and Humidity vs Defect Status](images/Material%20type%20and%20Humidity%20vs%20Defect%20status.png)

---

### Shift vs Defect Status

![Shift vs Defect Status](images/Shift%20vs%20Defect%20status.png)

## 📌 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost Implementation
- Model Explainability using SHAP
- Streamlit Web Application

---

## 👨‍💻 Author

Kevin Johnson

GitHub:
https://github.com/kevinjoe1