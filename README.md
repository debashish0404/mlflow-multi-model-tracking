# 🚀 MLflow Multiple Models Experiment

This project demonstrates how to use **MLflow** to track, compare, and manage multiple machine learning models.

---

## 📌 Project Overview

In this project, I trained and compared several machine learning models including:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost
* SVM
* KNN
* AdaBoost
* Gradient Boosting
* Extra Trees
* Naive Bayes

Each model is tracked using **MLflow**, logging:

* Parameters
* Metrics
* Model artifacts

---

## 📊 MLflow Tracking UI

Below is an example of the MLflow UI showing multiple training runs:

![MLflow UI Screenshot](images/mlflow_ui.png)

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/mlflow-demo.git
cd mlflow-demo
```

### 2. Create virtual environment

```bash
python -m venv env
env\Scripts\activate   # On Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the project

```bash
python src/train.py
```

---

## 📈 Launch MLflow UI

```bash
mlflow ui
```

Then open:

```
http://127.0.0.1:5000
```

---

## 🧠 What I Learned

* How to track experiments using MLflow
* Logging metrics, parameters, and models
* Comparing multiple models visually
* Managing experiment runs

---

## 📦 Tech Stack

* Python
* Scikit-learn
* MLflow
* XGBoost

---

## ⭐ Future Improvements

* Add hyperparameter tuning
* Deploy best model
* Integrate with cloud MLflow tracking

---

## 👨‍💻 Author

Your Name
Debashish mishra
