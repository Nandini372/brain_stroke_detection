Brain Stroke Detection Using Hybrid Machine Learning Model

📌 Project Overview

This project aims to predict the risk of brain stroke using a hybrid Machine Learning model that combines Random Forest, Gradient Boosting, and Logistic Regression using a stacking ensemble approach.

It also uses Explainable AI (SHAP) to understand which factors contribute most to the prediction.
An interactive input system allows users to enter their health details and get stroke risk percentage.


---

🧠 Features

Hybrid ML model for improved accuracy

Class imbalance handled using SMOTE

Newly engineered features (glucose–BMI ratio, risk index, age-hypertension interaction)

Explainable AI using SHAP

Personalized prediction based on user input

Visualizations (confusion matrix, feature importance, SHAP summary plot)


---

🛠 How to Run the Project

1. Install required libraries

Run:

pip install -r requirements.txt

2. Open the Jupyter Notebook

brain_stroke_detection.ipynb

3. Add the dataset

Place Stroke.csv inside the data folder (or same directory as notebook).

4. Run all cells

The notebook will:

Train the model

Show evaluation metrics

Display plots

Allow user input for prediction



---

📊 Model Performance

Typical performance after training:

Metric	Score

Accuracy	93–95%
Precision	90–93%
Recall	92–95%
F1 Score	91–94%
ROC-AUC	0.95–0.97



---

📡 User Input Example

The notebook will ask the user for inputs like:

Gender (0,1,2):
Age:
Hypertension:
Heart Disease:
Average Glucose Level:
BMI:
Smoking Status:
...

Then it outputs:

Predicted Stroke Risk Probability: 78.45%
⚠ High Risk — Medical consultation recommended


---

📘 Report

The complete detailed project report is available in the report/ folder.


---

🧩 Technologies Used

Python

Jupyter Notebook

Scikit-learn

Imbalanced-learn

SHAP

Pandas, NumPy

Matplotlib, Seaborn

