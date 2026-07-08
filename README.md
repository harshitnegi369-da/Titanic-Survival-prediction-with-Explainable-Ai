# Titanic Survival Prediction with Explainable AI (LIME & SHAP)

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using various Machine Learning classification algorithms. Along with model training and evaluation, Explainable AI (XAI) techniques have been applied to understand how the model makes predictions.

The project demonstrates both **predictive modeling** and **model interpretability** using **LIME** and **SHAP**.

---

## Dataset
The dataset used in this project is the Titanic: Machine Learning from Disaster dataset, originally made available through Kaggle.
- **Dataset:** Titanic Dataset
- **Target Variable:** Survived
  - 0 → Did Not Survive
  - 1 → Survived

### Features Used

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Preprocessing
   - Handle Missing Values
   - Encode Categorical Features
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Train Multiple Classification Models
8. Compare Model Performance
9. Select Best Performing Model
10. Explain Model Predictions using LIME
11. Explain Model Predictions using SHAP

---

## Machine Learning Models Implemented

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost

---

## Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## Explainable AI (XAI)

### LIME (Local Interpretable Model-Agnostic Explanations)

LIME is used to explain the prediction of an individual passenger.

It provides:

- Prediction probabilities
- Feature contribution towards prediction
- Local explanation table

### SHAP (SHapley Additive exPlanations)

SHAP is used to understand feature importance and prediction behavior.

Implemented:

- SHAP Summary Plot (Global Explainability)
- SHAP Feature Importance Plot

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LIME
- SHAP
- Jupyter Notebook

---

## Project Structure

```
Titanic-Explainable-AI/
│
├── Titanic.ipynb
├── titanic.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository

```bash
git clone  https://github.com/harshitnegi369-da/Titanic-Explainable-AI.git
```

Move into the project directory

```bash
cd Titanic-Explainable-AI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Results

- Compared six classification algorithms.
- Selected the best-performing model based on evaluation metrics.
- Applied Explainable AI techniques to understand individual and overall model behavior.
- Used LIME for local prediction explanations.
- Used SHAP for local and global feature importance analysis.

---

## Future Improvements

- Add Partial Dependence Plot (PDP)
- Add Individual Conditional Expectation (ICE) Plot
- Hyperparameter Tuning
- Cross Validation
- Deploy using Streamlit or Flask

---


This project is developed for learning and educational purposes.
