# 🎓 Student Pass Prediction using Random Forest

A machine learning classification project that predicts whether a student will **Pass** or **Fail** based on academic performance indicators. The project demonstrates a complete supervised machine learning workflow using **Random Forest** with **GridSearchCV** for hyperparameter tuning.

---

## 📌 Project Overview

The objective of this project is to build an optimized classification model that predicts student outcomes using the following features:

* Study Hours
* Attendance Percentage
* Assignments Completed

The project follows industry-standard machine learning practices including:

* Data Exploration (EDA)
* Train-Test Split
* Hyperparameter Tuning
* Cross Validation
* Model Evaluation
* Experiment Tracking
* Model Persistence

---

## 🗂 Dataset

Features:

| Feature          | Description                     |
| ---------------- | ------------------------------- |
| study_hours      | Average study hours             |
| attendance_pct   | Attendance percentage           |
| assignments_done | Number of completed assignments |

Target Variable:

| Label | Meaning |
| ----- | ------- |
| 0     | Fail    |
| 1     | Pass    |

---

## ⚙️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Joblib
* Logging Module
* Google Colab

---

## 🚀 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis
4. Feature Selection
5. Train-Test Split
6. Random Forest Model
7. Hyperparameter Tuning using GridSearchCV
8. 5-Fold Cross Validation
9. Model Evaluation
10. Save Best Model
11. Store Experiment Results

---

## 🔍 Hyperparameter Grid

```python
param_grid = {
    "n_estimators": [10, 50, 100],
    "max_depth": [3, 5, 10]
}
```

Evaluation Metric:

* Weighted F1 Score

Cross Validation:

* 5-Fold

---

## 📊 Results

The notebook reports:

* Best Hyperparameters
* Best Cross Validation F1 Score
* Test Weighted F1 Score
* Classification Report
* Confusion Matrix
* Feature Importance

---

## 📁 Project Structure

```text
student-pass-prediction-random-forest/
│
├── data/
├── notebook/
├── outputs/
├── images/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/<your-username>/student-pass-prediction-random-forest.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook using Google Colab or Jupyter Notebook.

---

## 📈 Future Improvements

* Compare multiple classification algorithms
* Perform feature engineering
* Build a deployment-ready web application
* Evaluate additional metrics such as ROC-AUC
* Use a larger real-world dataset

---

## 👨‍💻 Author

**Tarun Karn**

Final Year Computer Engineering Student

Passionate about Artificial Intelligence, Machine Learning, and Data Science.
