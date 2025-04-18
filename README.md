# Predict-Credit-Card-Fraud using Machine Learning

This project aims to detect fraudulent credit card transactions using machine learning techniques. We use a Random Forest Classifier to classify transactions as either **fraudulent** or **legitimate**, based on patterns in transaction data such as amount, timing, and user behavior.

---

## 📌 Problem Statement

**Objective:**  
Develop a classification model to detect fraudulent transactions based on patterns in transaction amount, location, device usage, and user behavior.

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Google Colab**
- **Pandas** – data manipulation  
- **NumPy** – numerical operations  
- **Matplotlib & Seaborn** – visualization  
- **Scikit-learn** – machine learning algorithms & metrics

---

## 📂 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection]
- **Description:** Contains transactions made by European cardholders in September 2013. Features are anonymized (V1 to V28), with `Time`, `Amount`, and `Class` columns.  
  - `Class 0` = Legitimate Transaction  
  - `Class 1` = Fraudulent Transaction

---

## 🔍 Project Workflow

### ✅ Step-by-Step:

1. **Install & Import Libraries**
2. **Load the Dataset** (Uploaded via Kaggle)
3. **Basic Data Exploration**
4. **Separate Features & Target**
5. **Split Data into Training & Testing Sets**
6. **Train the Model (Random Forest Classifier)**
7. **Make Predictions**
8. **Evaluate Model Performance**
9. **Visualize Confusion Matrix**

---

## 📊 Results

- The Random Forest model achieved strong performance on the imbalanced dataset.
- Evaluation metrics such as **accuracy**, **precision**, **recall**, and **F1-score** were used.
- A **confusion matrix** was plotted to visualize true vs. predicted labels.

---

## 📈 Sample Output

```python
Accuracy: 0.9991

Classification Report:
              precision    recall  f1-score   support

           0       1.00      1.00      1.00     56863
           1       0.91      0.81      0.86        99

    accuracy                           1.00     56962
   macro avg       0.95      0.91      0.93     56962
weighted avg       1.00      1.00      1.00     56962
