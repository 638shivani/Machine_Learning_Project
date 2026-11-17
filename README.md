# Diabetes Prediction Using Genetic Data 🧬

## 📌 Project Overview

Diabetes Prediction Using Genetic Data is a Machine Learning-based healthcare project that aims to predict diabetes and non-diabetes conditions using genetic, family-history, demographic, and medical information.

The project uses three machine learning algorithms: XGBoost, LightGBM, and CatBoost. Their performance is evaluated and compared to identify the best-performing model.

## 🎯 Project Objectives

- Analyze genetic and medical information.
- Perform data preprocessing and feature engineering.
- Handle imbalanced datasets using SMOTE.
- Train and compare multiple machine learning algorithms.
- Evaluate model performance using different evaluation metrics.
- Develop a user-friendly Gradio interface.

## 📂 Dataset Description

- Total Records: 21,011
- Total Features: 43 input features and 1 target column.
- Target Variable: Disorder Subclass
- Prediction Classes:
  - Diabetes
  - Non-Diabetes

The dataset includes genetic inheritance indicators, maternal and paternal gene information, family history, demographic details, and medical features.

## 🛠️ Technologies and Libraries

- Programming Language: Python
- Development Environment: Google Colab
- Data Processing: Pandas, NumPy
- Machine Learning: Scikit-learn
- Algorithms: XGBoost, LightGBM, CatBoost
- Data Balancing: SMOTE
- Data Visualization: Matplotlib, Seaborn
- User Interface: Gradio

## ⚙️ Project Workflow

1. Dataset Collection and Loading
2. Data Cleaning and Preprocessing
3. Removal of Unnecessary Columns
4. Handling Missing Values
   - Median for numerical features
   - Mode for categorical features
5. Categorical Feature Encoding using Label Encoding
6. Feature Scaling using StandardScaler
7. Train-Test Split (80:20)
8. Handling Class Imbalance using SMOTE on training data
9. Model Training
10. Model Evaluation and Comparison
11. Selection of the Best Performing Model
12. Development of Gradio Interface

## 🤖 Machine Learning Algorithms

### 1. XGBoost
Extreme Gradient Boosting is an ensemble learning algorithm that combines multiple decision trees to improve prediction performance.

### 2. LightGBM
Light Gradient Boosting Machine is a gradient boosting algorithm designed for efficient and faster model training.

### 3. CatBoost
CatBoost is a gradient boosting algorithm that provides effective handling of categorical features and improves prediction performance.

## 📊 Model Performance Comparison

The following results were obtained by evaluating the three algorithms using the uploaded dataset.

| Algorithm | Training Accuracy | Testing Accuracy |
|---|---:|---:|
| XGBoost | 99.69% | 91.43% |
| LightGBM | 96.98% | 91.70% |
| CatBoost | 97.78% | 91.72% |

### Best Performing Model

XGBoost achieved the highest testing accuracy of 91.72% in this evaluation.

## 📈 Model Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

These metrics help compare model performance and understand classification errors.



## 🚀 Future Enhancements

- Improve prediction performance through hyperparameter tuning.
- Add additional machine learning algorithms.
- Improve the prediction interface using a trained model.
- Deploy the application as a web-based healthcare prediction tool.
- Perform further validation using independent datasets.

## 👩‍💻 My Contribution

- Data preprocessing and cleaning.
- Feature engineering and handling missing values.
- Applying SMOTE to address class imbalance.
- Training XGBoost, LightGBM, and CatBoost models.
- Evaluating and comparing model performance.
- Selecting the best-performing algorithm.
- Developing the Gradio user interface.

## ⚠️ Disclaimer

This project is developed for academic and educational purposes. Its predictions are not a substitute for professional medical diagnosis or clinical testing.

