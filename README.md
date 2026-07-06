# 🏕️ Machine Learning Basecamp

> A complete, beginner-friendly Machine Learning repository — from raw data to advanced models.
> Every concept is backed by theory, real-world intuition, and hands-on projects.

---

## 📚 Series Roadmap

| Part | Topic | Status |
|------|-------|--------|
| Part 0 — Statistics Foundations | Z-Test, T-Test, ANOVA, Chi-Square, Outlier Detection | ✅ Done |
| Part 1 — Foundations | EDA, Data Cleaning, Feature Engineering | ✅ Done |
| Part 2 — Regression | Linear Regression, Cost Function, Gradient Descent | ✅ Done |
| Part 3 — Classification | Logistic Regression, KNN, SVM, Decision Trees, Naive Bayes | ✅ Done |
| Part 4 — Advanced ML | Ensemble Methods, Clustering, PCA, XGBoost | ✅ Done |
| Part 5 — Real-World Projects | End-to-end ML apps with Streamlit dashboards | ✅ Done |

---

## 📂 Repository Structure

```
ML MODELS/
├── 00_Statistics_Foundations/        # Statistical tests for ML
│   ├── 01_Z_Test.ipynb                  - Z-Test for population means
│   ├── 02_One_Sample_T_Test.ipynb       - One-sample T-Test
│   ├── 03_Two_Sample_T_Test.ipynb       - Welch's T-Test comparison
│   ├── 04_ANOVA_Test.ipynb              - One-Way ANOVA analysis
│   ├── 05_Chi_Square_Test.ipynb         - Chi-Square independence test
│   └── 06_Outlier_Detection.ipynb       - IQR-based outlier detection
│
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
├── 06_Projects/                      # Full projects (local + external)
│   ├── 01_Gym_Members_Analysis.ipynb     - Workout data analysis
│   ├── 02_Insurance_ML_Project.ipynb     - Complete ML project
│   └── 🔗 See "Real-World Projects" section below for deployed apps
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

## Part 0 — Statistics Foundations 📊

> *"The math behind ML — hypothesis testing, significance, and data validation."*

### What You'll Learn
- Z-Test — population mean testing
- One-Sample & Two-Sample T-Tests — comparing group means
- ANOVA — testing differences across multiple groups
- Chi-Square Test — categorical feature independence
- Outlier Detection — IQR method for anomaly identification

### 📂 Notebooks

| # | Notebook | Concept | Dataset |
|---|----------|---------|---------|
| 01 | [`01_Z_Test.ipynb`](./ML%20MODELS/00_Statistics_Foundations/01_Z_Test.ipynb) | Z-Test for population means | Titanic |
| 02 | [`02_One_Sample_T_Test.ipynb`](./ML%20MODELS/00_Statistics_Foundations/02_One_Sample_T_Test.ipynb) | One-sample T-Test | Titanic |
| 03 | [`03_Two_Sample_T_Test.ipynb`](./ML%20MODELS/00_Statistics_Foundations/03_Two_Sample_T_Test.ipynb) | Welch's T-Test | Titanic |
| 04 | [`04_ANOVA_Test.ipynb`](./ML%20MODELS/00_Statistics_Foundations/04_ANOVA_Test.ipynb) | One-Way ANOVA | Titanic |
| 05 | [`05_Chi_Square_Test.ipynb`](./ML%20MODELS/00_Statistics_Foundations/05_Chi_Square_Test.ipynb) | Chi-Square independence | Titanic |
| 06 | [`06_Outlier_Detection.ipynb`](./ML%20MODELS/00_Statistics_Foundations/06_Outlier_Detection.ipynb) | IQR outlier detection | Titanic |

**Source:** Pulled from [ML-Statistics-Foundations](https://github.com/loisekk/ML-Statistics-Foundations)

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

## Part 5 — Real-World Projects 🌍

> *Production-grade ML applications — end-to-end pipelines, deployed dashboards, and real data.*

---

### 🏎️ F1 Strategy Engine

> Production-grade binary classification on **101,371 real F1 telemetry laps** — predicting optimal pit stop windows using tyre degradation signals, race position dynamics, and lap time decay.

![F1 Strategy Engine Demo](https://raw.githubusercontent.com/loisekk/f1-strategy-engine/main/assets/f1_strategy_app.gif)

| Metric | Value |
|--------|-------|
| Accuracy | **97%** (LightGBM) |
| Best F1 Score | **0.9445** |
| Best CV AUC | **0.9869** (XGBoost) |
| Data | 101,371 laps · 2022–2025 season |
| Tech | XGBoost, LightGBM, Streamlit, Plotly 3D |

🔗 [**View Repo**](https://github.com/loisekk/f1-strategy-engine) · [**Live Demo**](https://f1-strategy-engine-asghcuc5n7idh2ucgk7upy.streamlit.app/)

---

### 🚗 Ford Car Price Prediction

> End-to-end ML pipeline on **17,966 real Ford vehicle listings** — premium dark-themed Streamlit dashboard with 3D Plotly visualizations, live price prediction gauge, and animated market analysis.

![Ford Car Price Dashboard](https://raw.githubusercontent.com/loisekk/Ford-Car-Price-Prediction/main/assets/car_price_app.gif)

| Metric | Value |
|--------|-------|
| R² Score | **0.91** (Random Forest) |
| Data | 17,966 UK Ford listings |
| Features | 3D Plotly charts, live prediction gauge, bubble animations |
| Tech | Random Forest, Streamlit, Plotly, Scikit-learn |

🔗 [**View Repo**](https://github.com/loisekk/Ford-Car-Price-Prediction)

---

### 🏥 CordisAI Heart Prediction

> Clinical decision-support dashboard for **cardiovascular risk assessment** — dark medical-themed UI, patient radar charts, risk probability gauges, benchmarked across 5 algorithms on 918 real patients.

![CordisAI Heart Dashboard](https://raw.githubusercontent.com/loisekk/Cordisai-heart-prediction/main/assets/Heart_disease_look.gif)

| Metric | Value |
|--------|-------|
| Accuracy | **86.4%** (KNN) |
| F1 Score | **88.2%** |
| Algorithms | KNN, Logistic Regression, Naive Bayes, SVM, Decision Tree |
| Data | 918 real patients |
| Tech | KNN, Streamlit, Plotly, Joblib |

🔗 [**View Repo**](https://github.com/loisekk/Cordisai-heart-prediction)

---

### 📈 Stock Price Prediction

> Next-day stock closing price prediction using **correlated multi-stock signals**, temporal lag features, and rolling market statistics across 5 correlated stocks.

![Stock Price Dashboard](https://raw.githubusercontent.com/loisekk/Stock-Price-Prediction/main/assets/stock-price-dash.gif)

| Metric | Value |
|--------|-------|
| Best Model | **Linear Regression** (saved to production) |
| Features | 14 engineered (lag-1/lag-2, 5-day MA, volatility, cross-stock signals) |
| Stocks | 5 correlated tickers |
| Tech | Linear Regression, XGBoost, SVR, Random Forest, Streamlit |

🔗 [**View Repo**](https://github.com/loisekk/Stock-Price-Prediction)

---

### 🎓 Edumind Student Performance

> Full-stack ML project following the **F1 methodology** — XGBoost ensemble with Voting, Stacking, and Blending. Supabase integration, Flask frontend, and production-ready ColumnTransformer pipeline.

| Metric | Value |
|--------|-------|
| R² Score | **0.9984** (Production Pipeline) |
| MAE | **0.4036** |
| Ensemble | Voting, Stacking, Blending |
| Tuning | RandomizedSearchCV + GridSearchCV |
| Tech | XGBoost, LightGBM, Flask, Supabase |

🔗 [**View Repo**](https://github.com/loisekk/Edumind-student-performance)

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific-013243?logo=numpy)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-FF6F00?logo=xgboost)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B?logo=streamlit)
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
