# Cyber Security Case Study -
## 📖 Project Overview


This project builds a Machine Learning based Intrusion Detection System (IDS) to detect cyber attacks in network traffic.

The system performs:

1. Binary Classification  
   - Normal vs Attack  

2. Multiclass Classification  
   - Normal  
   - Back  
   - BufferOverflow  
   - FTPWrite  
   - GuessPassword  
   - Neptune  
   - NMap  
   - PortSweep  
   - RootKit  
   - Satan  
   - Smurf  

---

## 🎯 Business Objective

To build a machine learning model capable of detecting network intrusions and identifying the type of cyber attack using network traffic features.

---

## 📊 Dataset Description

- 41 Network Features
- Combination of:
  - Basic features
  - Content-based features
  - Time-based traffic features
  - Host-based traffic features
- Highly imbalanced dataset

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Random Forest Classifier
- Jupyter Notebook

---

## 🧠 Machine Learning Approach

1. Data Merging (11 CSV files)
2. Feature Engineering
3. One-Hot Encoding
4. Handling Missing Values
5. SMOTE for Imbalance Handling
6. Model Training (Random Forest)
7. Model Evaluation

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🚀 Results

The model successfully detects network attacks with high precision and recall.
SMOTE improved detection of minority attack classes.

---

## 📂 Project Structure
