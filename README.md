# AIML-TASK-4-Classification-with-Logistic-Regression-
# 🧠 Breast Cancer Classification using Logistic Regression

## 📌 Objective
This project is part of **Task 4** of the AI & ML Internship. The goal is to build a binary classification model using **Logistic Regression** to predict whether a tumor is **benign (0)** or **malignant (1)** using the **Breast Cancer Wisconsin dataset**.

---

## 📁 Dataset
- **Name:** Breast Cancer Wisconsin Diagnostic Dataset
- **Source:** [Kaggle Link](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

---

## 🛠 Tools & Libraries
- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Seaborn, Matplotlib

---

## 🔍 Steps Performed

### 1. Data Preprocessing
- Removed ID column
- Converted diagnosis labels (M → 1, B → 0)
- Checked and handled null values
- Selected only numeric features

### 2. Model Training
- Standardized features using `StandardScaler`
- Trained a `LogisticRegression` model using `sklearn`

### 3. Model Evaluation
- Evaluated predictions with:
  - **Confusion Matrix**
  - **Classification Report** (Precision, Recall, F1-Score)
  - **ROC-AUC Score**
- Plotted the **ROC Curve**

---

## 📈 Key Evaluation Metrics

|     Metric     |         Value (Example)               |
|----------------|---------------------------------------|
| Accuracy       | 96–98%                                |
| Precision      | High (esp. for Malignant class)       |
| Recall         | High (important in medical diagnosis) |
| ROC-AUC Score  | ~0.99                                 |

---

## 📊 Visuals Included
- ROC Curve showing model performance
- Confusion matrix

---

## Submitted by: MUMMADI RAMCHARAN

---


