# Machine Learning - Disaster Prediction and Classification with Ensemble Models

This project focuses on leveraging machine learning models—specifically ensemble methods like Random Forest and Gradient Boosting—to predict and classify natural disasters such as floods, hurricanes, and wildfires. Using FEMA disaster data, we preprocess features, address class imbalance through synthetic sampling, and compare multiple models to assess predictive performance.

## 🚀 Key Features

- Preprocessing of FEMA disaster records (handling missing values, encoding, scaling)
- Synthetic data generation to handle class imbalance
- Comparative model evaluation (Logistic Regression, Decision Tree, SVM, Random Forest, Gradient Boosting)
- Hyperparameter tuning with Stratified K-Fold CV
- Performance metrics: Accuracy, F1-score, ROC-AUC

## 📊 Results

Gradient Boosting achieved the highest performance:
- Accuracy: **98.2%**
- F1-Score: **98.2%**
- AUC: **0.9987**

## 🛠 Technologies

- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
- FEMA Open Dataset

## ✅ Future Improvements

- Incorporate real-time weather data feeds
- Explore transformer-based deep learning models for spatio-temporal forecasting
- Extend geographic generalizability

## 📁 Files

- `model_comparison.ipynb`: Jupyter notebook with full pipeline and analysis
-  FEMA Preprocessed Data.csv

