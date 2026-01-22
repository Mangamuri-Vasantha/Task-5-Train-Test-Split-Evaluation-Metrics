# Task-5-Train-Test-Split-Evaluation-Metrics
# Task 5: Train-Test Split & Evaluation Metrics (Heart Disease Dataset)

## 📌 Objective
The objective of this task is to understand how to:
- Split a dataset into training and testing sets  
- Train a simple machine learning model  
- Evaluate the model using standard evaluation metrics  

This task uses the **Heart Disease Dataset** and applies **Logistic Regression** for classification.

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- Scikit-learn  

---

## 📂 Dataset
**Heart Disease Dataset (`heart.csv`)**

The dataset contains medical attributes of patients and a target column:
- `target = 1` → Patient has heart disease  
- `target = 0` → Patient does not have heart disease  

---

## 🔍 Steps Performed

### 1. Load the Dataset
The dataset is loaded using Pandas and basic inspection is done using `head()`.

### 2. Split Features and Target
- Features (`X`) → All columns except `target`  
- Target (`y`) → `target` column  

### 3. Train-Test Split
The data is split into:
- 80% Training data  
- 20% Testing data  

This helps evaluate how well the model generalizes to unseen data.

### 4. Train the Model
A **Logistic Regression** model is trained using the training dataset.

### 5. Make Predictions
Predictions are made on the test dataset.

### 6. Evaluate the Model
The following metrics are calculated:
- **Accuracy** – Overall correctness of the model  
- **Precision** – Correct positive predictions out of all predicted positives  
- **Recall** – Correct positive predictions out of all actual positives  
- **Confusion Matrix** – Shows True Positives, True Negatives, False Positives, and False Negatives  

A full **classification report** is also generated.

---

## 📊 Evaluation Metrics Used

- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  
- Classification Report  

These metrics help understand both overall performance and class-wise performance.

---

## 📁 Files in Repository
- `heart.csv` → Dataset  
- `heart.py` (or notebook) → Python code for training and evaluation  
- `README.md` → Task explanation  

---

## ✅ Outcome
- Successfully trained a Logistic Regression model  
- Evaluated model performance using multiple metrics  
- Gained understanding of:
  - Train vs Test split  
  - Overfitting prevention  
  - Model evaluation fundamentals  

---

## 💡 Key Learnings
- Why splitting data is important  
- Difference between accuracy, precision, and recall  
- How confusion matrix helps interpret model predictions  

---
