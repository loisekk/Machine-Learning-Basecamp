# 🌍 Real-World Projects

> Production-grade ML applications — end-to-end pipelines, deployed dashboards, and real data.

---

## 🏎️ F1 Strategy Engine

> Binary classification on **101,371 real F1 telemetry laps** — predicting optimal pit stop windows using tyre degradation signals, race position dynamics, and lap time decay.

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

## 🚗 Ford Car Price Prediction

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

## 🏥 CordisAI Heart Prediction

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

## 📈 Stock Price Prediction

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

## 🎓 Edumind Student Performance

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

## 📊 Project Stats

| Domain | Projects | Best Model | Top Metric |
|--------|----------|------------|------------|
| 🏎️ Motorsport | F1 Strategy Engine | XGBoost | AUC 0.99 |
| 🚗 Automotive | Ford Car Price | Random Forest | R² 0.91 |
| 🏥 Healthcare | CordisAI Heart | KNN | Acc 86.4% |
| 📈 Finance | Stock Price | Linear Regression | R² 0.91 |
| 🎓 Education | Edumind Student | XGBoost | R² 0.9984 |

---

## 🛠️ Tech Stack Across Projects

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B?logo=streamlit)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-FF6F00?logo=xgboost)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?logo=scikit-learn)
![Plotly](https://img.shields.io/badge/Plotly-Visualizations-3F4F75?logo=plotly)
![Supabase](https://img.shields.io/badge/Supabase-Database-3FCF8E?logo=supabase)
