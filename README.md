# 📊 Predictive Modeling I - Lecture & Practical Lab

## 📁 Files Included
- Predictive_Modeling_Lecture_Updated.docx → Complete lecture notes  
- Predictive_Modeling_Lab_Colab_Updated.ipynb → Hands-on practical lab  

---

## 🚀 How to Run This Lab (Google Colab)

1. Open Google Colab: https://colab.research.google.com  
2. Click on **Upload Notebook**  
3. Upload file: `Predictive_Modeling_Lab_Colab_Updated.ipynb`  
4. Run each cell **step by step (top → bottom)**  

⚠️ Important:  
Do NOT skip any cell — each step depends on the previous one.

---

## 🎯 Learning Objectives

After completing this lab, students will be able to:

- Understand **Predictive Modeling concepts**
- Work with real datasets
- Perform **Train-Test Split**
- Apply **Feature Scaling**
- Train multiple Machine Learning models:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest
- Evaluate models using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Compare models and select the **best performing model**

---

## 🧠 Real-Life Applications

This lab represents real-world use cases such as:

- 📞 Telecom → Predict customer churn  
- 🏦 Banking → Predict loan default  
- 🛒 E-commerce → Predict customer purchase behavior  
- 🏥 Healthcare → Predict diseases  

👉 Goal: Use historical data to make smart predictions about future outcomes.

---

## 🧪 Student Practice Tasks

After completing all lab cells, students must complete the following tasks:

### 🔹 Task 1: Change KNN Value
- Modify `n_neighbors = 5` to:
  - 3  
  - 7  
- Run the model again and compare results  

👉 Question: Which value gives better performance?

---

### 🔹 Task 2: Improve Random Forest
- Change:
  - `n_estimators = 200` → try 50, 100, 300  
- Observe the changes in performance  

👉 Question: Does increasing trees always improve accuracy?

---

### 🔹 Task 3: Run Without Scaling
- Run Logistic Regression **without scaling**  

👉 Compare results  
👉 Question: Why is scaling important?

---

### 🔹 Task 4: Add New Model (Challenge)
Try adding a new model:

```python
from sklearn.tree import DecisionTreeClassifier