# 🏕️ Machine Learning Basecamp

> A complete, beginner-friendly Machine Learning repository — from raw data to advanced models.
> Every concept is backed by theory, real-world intuition, and hands-on projects.

---

## 📚 Series Roadmap

| Part | Topic | Status |
|------|-------|--------|
| Part 1 — Foundations | EDA, Data Cleaning, Feature Engineering | ✅ Done |
| Part 2 — Regression | Linear Regression, Cost Function, Gradient Descent | ✅ Done |
| Part 3 — Classification | Logistic Regression, KNN, SVM, Decision Trees, Naive Bayes | ✅ Done |
| Part 4 — Advanced ML | Ensemble Methods, Clustering, PCA, XGBoost | ✅ Done |

---

## Part 1 — ML Foundations

> *"Most critical and often ignored steps in ML — but they make or break your model's success."*

### What You'll Learn
- How to define a problem clearly
- Where and how to collect quality data
- Exploratory Data Analysis (EDA) — the right way
- Data Cleaning & Preprocessing techniques
- Feature Selection — choosing what matters
- Feature Engineering — boosting model performance

---

### 🔬 Projects

#### 📌 Project 1 — Heart Disease EDA & Preprocessing

Performed full EDA on a clinical heart disease dataset. Key work includes:
- Handled zero-value anomalies in `Cholesterol` and `RestingBP` via mean imputation
- Visualized distributions using histplots and violin plots
- Explored feature relationships using heatmaps and countplots
- Applied One-Hot Encoding for categorical features
- Scaled numerical features using `StandardScaler` — model-ready output

**Notebook:** [`Heart_Dataframe.ipynb`](./Heart_Dataframe.ipynb)

---

#### 📌 Project 2 — Insurance Charges EDA & Feature Engineering

End-to-end preprocessing pipeline on a medical insurance dataset. Key work includes:
- Applied Label Encoding for binary columns (`sex`, `smoker`)
- Applied One-Hot Encoding for the `region` column
- Engineered a new `bmi_category` feature (Underweight / Normal / Overweight / Obese)
- Used **Pearson Correlation** for numerical feature selection
- Used **Chi-Square Test** for categorical feature selection
- Final feature set selected for predicting insurance `charges`

**Notebook:** [`Insurance_Dataframe.ipynb`](./Insurance_Dataframe.ipynb)

---

## 🔜 Coming Soon

### Part 2 — Regression
- Linear Regression — concept and intuition
- Cost Function & Gradient Descent
- Model Evaluation: MSE, RMSE, R² Score
- Train-Test Split — why it matters
- Overfitting vs Underfitting with visuals
- **Project:** House Price Prediction

### Part 3 — Classification
- Logistic Regression, KNN, Decision Trees, Naive Bayes, SVM
- Evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- **Project:** Titanic Survival Classification

### Part 4 — Advanced ML
- Cross-Validation & Hyperparameter Tuning (Grid Search, Random Search)
- Ensemble Learning — Bagging, Boosting, Stacking
- Random Forest, AdaBoost, Gradient Boosting, XGBoost
- Unsupervised Learning — K-Means, DBSCAN
- Dimensionality Reduction — PCA
- **Projects:** Clustering & PCA visualizations

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific-013243?logo=numpy)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c72b0)

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/machine-learning-basecamp.git
cd machine-learning-basecamp
pip install -r requirements.txt
```

Open any notebook in Jupyter or Google Colab and follow along.

---

## ⭐ Support

If this repo helped you, consider giving it a star — it helps others find it too!
