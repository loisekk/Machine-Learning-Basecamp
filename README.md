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

## 📂 Repository Structure

```
ML MODELS/
├── 01_Regression/                    # Regression models
│   ├── 01_Linear_Regression.ipynb        - Food delivery time prediction
│   ├── 02_Food_Delivery_Time_Prediction  - Extended EDA + modeling
│   ├── 03_Calories_Burn_Prediction       - Random Forest regressor
│   ├── 04_House_Price_Prediction         - Real estate price prediction
│   └── 05_Insurance_Charges_Prediction   - Medical insurance cost prediction
│
├── 02_Classification/                # Classification models
│   ├── 01_Logistic_Regression.ipynb      - Titanic survival
│   ├── 02_KNN.ipynb                      - Student performance classification
│   ├── 03_Naive_Bayes.ipynb              - Credit card churn prediction
│   ├── 04_Decision_Tree.ipynb            - Heart disease classification
│   ├── 05_Loan_Approval_Prediction       - Random Forest classifier
│   ├── 06_Online_Shoppers_Revenue        - Purchase intention prediction
│   ├── 07_Titanic_Survival_Prediction    - Extended multi-model analysis
│   ├── 08_Heart_Disease_AdaBoost         - AdaBoost on heart data
│   ├── 09_Heart_Disease_Full_Pipeline    - Complete EDA + classification
│   ├── 10_Customer_Churn_Prediction      - Logistic Regression on churn
│   └── 11_Shoppers_Intention_Prediction  - Automated EDA + classification
│
├── 03_Ensemble_Methods/              # Ensemble & boosting techniques
│   ├── 01_Bagging_Random_Forest.ipynb    - Bagging + RF + Stacking
│   ├── 02_AdaBoost_Gradient_XGBoost      - Three boosting methods compared
│   ├── 03_Multi_Model_Comparison         - LR, SVM, NB, KNN, DT benchmark
│   ├── 04_Cross_Validation               - K-Fold & Stratified CV
│   ├── 05_Gradient_Boosting_Regression   - Insurance charges prediction
│   ├── 06_Grid_Search_CV                 - Hyperparameter tuning
│   └── 07_Stacking_Classifier            - Stacking with meta-learner
│
├── 04_Clustering/                    # Unsupervised learning
│   ├── 01_Hierarchical_Clustering.ipynb  - Country socio-economic groups
│   └── 02_KMeans_Clustering.ipynb        - Elbow method + cluster analysis
│
├── 05_Preprocessing/                 # Data preparation & EDA
│   ├── 01_SKLearn_Pipelines.ipynb        - End-to-end ML pipelines
│   ├── 02_SMOTE_Imbalance_Handling       - Class imbalance with SMOTE
│   ├── 03_Heart_Disease_EDA.ipynb        - Correlation, scaling, encoding
│   ├── 04_Insurance_Data_EDA.ipynb       - Feature engineering pipeline
│   └── 05_EV_Population_EDA.ipynb        - Electric vehicle data analysis
│
├── 06_Projects/                      # Full projects
│   ├── 01_Gym_Members_Analysis.ipynb     - Workout data analysis
│   └── 02_Insurance_ML_Project.ipynb     - Complete ML project
│
├── 07_NLP/                           # Natural Language Processing
│   ├── LR_SVM_NB_K_NN_DT.ipynb          - NLP text classification
│   └── train.txt                         - Training data
│
└── datasets/                         # All datasets
    ├── Food_Delivery_Times.csv
    ├── calories.csv
    ├── customer_churn_prediction_dataset.csv
    ├── heart.csv
    ├── House_Price_Dataset.csv
    ├── Adaboost_heart.csv
    ├── gym_members_exercise_tracking.csv
    ├── online_shoppers_intention.csv
    ├── global_power_plant_database.csv
    ├── expenses.csv
    └── ...
```

---

## Part 1 — ML Foundations 🧱

> *"Most critical and often ignored steps in ML — but they make or break your model's success."*

### What You'll Learn
- How to define a problem clearly
- Where and how to collect quality data
- Exploratory Data Analysis (EDA) — the right way
- Data Cleaning & Preprocessing techniques
- Feature Selection — choosing what matters
- Feature Engineering — boosting model performance

### 🔬 Projects

#### 📌 Project 1 — Heart Disease EDA & Preprocessing

Performed full EDA on a clinical heart disease dataset. Key work includes:
- Handled zero-value anomalies in `Cholesterol` and `RestingBP` via mean imputation
- Visualized distributions using histplots and violin plots
- Explored feature relationships using heatmaps and countplots
- Applied One-Hot Encoding for categorical features
- Scaled numerical features using `StandardScaler` — model-ready output

**Notebook:** [`03_Heart_Disease_EDA.ipynb`](./ML%20MODELS/05_Preprocessing/03_Heart_Disease_EDA.ipynb)

---

#### 📌 Project 2 — Insurance Charges EDA & Feature Engineering

End-to-end preprocessing pipeline on a medical insurance dataset. Key work includes:
- Applied Label Encoding for binary columns (`sex`, `smoker`)
- Applied One-Hot Encoding for the `region` column
- Engineered a new `bmi_category` feature (Underweight / Normal / Overweight / Obese)
- Used **Pearson Correlation** for numerical feature selection
- Used **Chi-Square Test** for categorical feature selection
- Final feature set selected for predicting insurance `charges`

**Notebook:** [`04_Insurance_Data_EDA.ipynb`](./ML%20MODELS/05_Preprocessing/04_Insurance_Data_EDA.ipynb)

---

## Part 2 — Regression 📈

### What You'll Learn
- Linear Regression — concept and intuition
- Cost Function & Gradient Descent
- Model Evaluation: MSE, RMSE, R² Score
- Train-Test Split — why it matters
- Overfitting vs Underfitting with visuals

### 🔬 Projects

#### 📌 Food Delivery Time Prediction
Predicts delivery time using distance, weather, traffic, and vehicle type.
**Notebook:** [`01_Linear_Regression.ipynb`](./ML%20MODELS/01_Regression/01_Linear_Regression.ipynb)

#### 📌 House Price Prediction
Real estate price prediction with extensive EDA and plotly visualizations.
**Notebook:** [`04_House_Price_Prediction.ipynb`](./ML%20MODELS/01_Regression/04_House_Price_Prediction.ipynb)

#### 📌 Calories Burn Prediction
Predicts calories burned during exercise using Random Forest.
**Notebook:** [`03_Calories_Burn_Prediction.ipynb`](./ML%20MODELS/01_Regression/03_Calories_Burn_Prediction.ipynb)

---

## Part 3 — Classification 🏷️

### What You'll Learn
- Logistic Regression, KNN, Decision Trees, Naive Bayes, SVM
- Evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

### 🔬 Projects

#### 📌 Titanic Survival Classification
Binary classification to predict passenger survival on the Titanic.
**Notebook:** [`07_Titanic_Survival_Prediction.ipynb`](./ML%20MODELS/02_Classification/07_Titanic_Survival_Prediction.ipynb)

#### 📌 Loan Approval Prediction
Random Forest classifier for loan approval decisions.
**Notebook:** [`05_Loan_Approval_Prediction.ipynb`](./ML%20MODELS/02_Classification/05_Loan_Approval_Prediction.ipynb)

#### 📌 Customer Churn Prediction
Logistic Regression on telecom customer churn data.
**Notebook:** [`10_Customer_Churn_Prediction.ipynb`](./ML%20MODELS/02_Classification/10_Customer_Churn_Prediction.ipynb)

---

## Part 4 — Advanced ML 🚀

### What You'll Learn
- Cross-Validation & Hyperparameter Tuning (Grid Search, Random Search)
- Ensemble Learning — Bagging, Boosting, Stacking
- Random Forest, AdaBoost, Gradient Boosting, XGBoost
- Unsupervised Learning — K-Means, Hierarchical Clustering
- Dimensionality Reduction — PCA

### 🔬 Projects

#### 📌 Multi-Model Comparison
Benchmark of LR, SVM, Naive Bayes, KNN, and Decision Tree on Titanic data.
**Notebook:** [`03_Multi_Model_Comparison.ipynb`](./ML%20MODELS/03_Ensemble_Methods/03_Multi_Model_Comparison.ipynb)

#### 📌 Boosting Methods Compared
AdaBoost, Gradient Boosting, and XGBoost head-to-head on Iris classification.
**Notebook:** [`02_AdaBoost_Gradient_XGBoost.ipynb`](./ML%20MODELS/03_Ensemble_Methods/02_AdaBoost_Gradient_XGBoost.ipynb)

#### 📌 Country Clustering
KMeans and Hierarchical Clustering on country socio-economic data.
**Notebook:** [`01_Hierarchical_Clustering.ipynb`](./ML%20MODELS/04_Clustering/01_Hierarchical_Clustering.ipynb)

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
git clone https://github.com/loisekk/Machine-Learning-Basecamp.git
cd Machine-Learning-Basecamp
pip install -r requirements.txt
```

Open any notebook in Jupyter or Google Colab and follow along.

---

## ⭐ Support

If this repo helped you, consider giving it a star — it helps others find it too!
