# Brain Stroke Detection Using Hybrid Machine Learning Model

## Overview

This project predicts the risk of brain stroke using a hybrid machine learning model based on a stacking ensemble of Random Forest, Gradient Boosting, and Logistic Regression.

The model uses SMOTE to address class imbalance and SHAP for model interpretability, helping identify the key factors influencing stroke risk predictions.

## Features

* Hybrid ensemble learning approach
* Stroke risk prediction from patient health data
* SMOTE for handling imbalanced datasets
* Feature engineering for improved performance
* Explainable AI using SHAP
* Personalized risk prediction based on user inputs

## Technologies Used

* Python
* Scikit-learn
* SHAP
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Model Performance

| Metric    | Score     |
| --------- | --------- |
| Accuracy  | 93–95%    |
| Precision | 90–93%    |
| Recall    | 92–95%    |
| ROC-AUC   | 0.95–0.97 |

## How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Place `Stroke.csv` in the project directory.

3. Open and run `brain_stroke_detection.ipynb`.

## Future Improvements

* Web application deployment
* Real-time health monitoring
* Deep learning-based prediction models
* Cloud integration
