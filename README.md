# PolicyClaim

# 🚀 Insurance Claim Prediction – End-to-End Machine Learning Project

Welcome to my end-to-end machine learning project where I built a predictive model to determine whether a customer is likely to file an insurance claim within the next 6 months. This project covers the full data science lifecycle – from data ingestion, preprocessing, and handling class imbalance to model training, evaluation, and visualization.

---

## 📌 Problem Statement

Develop a classification model to predict whether a policyholder will file an insurance claim in the next 6 months, based on historical data about customer, vehicle, and policy attributes.

---

## 🔍 Key Highlights

### ✅ Data Handling & Storage
- Collected real-world insurance data from Kaggle (58,592 rows × 41 features).
- Stored and accessed data using **MS SQL Server** (localhost).
- Established Python-to-SQL connection via **SQLAlchemy** and **pyodbc**.

### 🧪 Data Analysis & Preprocessing
- Performed statistical analysis and extensive feature engineering.
- Handled categorical features using `OrdinalEncoding`.
- Addressed class imbalance using:
  - **SMOTE**
  - **pandas resample**
  - **SMOTEEN** (performed best in production).

### 🧠 Model Building & Evaluation
Trained and compared the following classification models:
- `RandomForestClassifier`
- `LogisticRegression`
- `LightGBM`
- `DecisionTreeClassifier`
- `AdaBoostClassifier`
- `GradientBoostingClassifier`
- `XGBoostClassifier`

#### Evaluation Metrics:
- **F1 Score** (primary metric)
- Precision
- Recall
- Accuracy

**Random Forest** was the top performer, and its robustness was validated with a **learning curve**.

---

## 🛠️ Tech Stack

- **Languages & Libraries**: Python, Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn, LightGBM, XGBoost
- **Database**: MS SQL Server (localhost) with SQLAlchemy and pyodbc
- **Imbalance Handling**: SMOTE, SMOTEEN, pandas.resample
- **IDE**: Jupyter Notebook

---

## 📊 Project at a Glance
- ✅ Built scalable data pipelines using SQL
- ✅ Applied advanced feature engineering techniques
- ✅ Effectively handled imbalanced data
- ✅ Selected and validated top-performing model using rigorous evaluation