# SVM – Breast Cancer Classification

## 📌 Project Overview

This project demonstrates **Support Vector Machine (SVM)**–based classification for **breast cancer diagnosis** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**. The objective is to classify tumors as **Malignant (M)** or **Benign (B)** and to help interns understand **kernel-based learning, feature scaling, hyperparameter tuning, and model evaluation**.

The project is implemented in **Python** using **Scikit-learn** and is designed to run smoothly on **Google Colab**.

---

## 🗂 Dataset

**Name:** Breast Cancer Wisconsin (Diagnostic) Dataset

### Dataset Description

* Total Samples: 569
* Features: 30 numeric features computed from digitized images of breast mass
* Target Variable:

  * `M` → Malignant (1)
  * `B` → Benign (0)

Unused columns (`id`, `Unnamed: 32`) are removed during preprocessing.

---

## 🛠 Tools & Technologies

* **Python 3**
* **Scikit-learn**
* **Pandas & NumPy**
* **Matplotlib**
* **Joblib** (for model saving)

### Alternatives (Not implemented)

* Weka
* R (caret package)

---

## 🔍 Project Workflow

1. Load and inspect the dataset
2. Encode target labels
3. Apply **StandardScaler** for feature normalization
4. Split data into training and testing sets
5. Train baseline SVM with **Linear Kernel**
6. Train SVM with **RBF Kernel**
7. Perform hyperparameter tuning using **GridSearchCV** (`C`, `gamma`)
8. Evaluate the best model using:

   * Confusion Matrix
   * Classification Report
   * ROC Curve & AUC Score
9. Save the trained **Scaler + SVM pipeline** for reuse

---

## 📈 Model Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* ROC Curve
* AUC (Area Under Curve)

The **RBF kernel with tuned hyperparameters** achieved the best performance.

---

## 📁 Project Files

| File Name                     | Description                                     |
| ----------------------------- | ----------------------------------------------- |
| `taak_11.ipynb`               | Jupyter Notebook containing full implementation |
| `data.csv`                    | Breast cancer dataset                           |
| `svm_breast_cancer_model.pkl` | Saved trained SVM pipeline                      |
| `README.md`                   | Project documentation                           |

---

## ▶ How to Run (Google Colab)

1. Open **Google Colab**
2. Upload the following files:

   * `taak_11.ipynb`
   * `data.csv`
3. Run the notebook cells sequentially
4. The trained model will be saved automatically as:

   ```
   svm_breast_cancer_model.pkl
   ```

---

## 🎯 Learning Outcomes

By completing this project, an intern will:

* Understand SVM theory and kernel functions
* Learn feature scaling importance
* Perform hyperparameter tuning using GridSearchCV
* Interpret classification metrics and ROC-AUC
* Build and save a reusable ML pipeline

---
# OUTPUT
<img width="522" height="414" alt="Image" src="https://github.com/user-attachments/assets/815d5b63-9c9a-4622-8ed7-940cdad9e2a8" />
