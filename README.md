# Customer Transaction Prediction

## 📌 Project Overview
This project aims to predict whether a bank customer will make a transaction in the future using machine learning techniques. The dataset is anonymized and contains high-dimensional numerical features, making the problem suitable for classification modeling and performance evaluation.

---

## 🎯 Problem Statement
Banks need to identify customers who are likely to make future transactions. The objective of this project is to build a predictive model that classifies customers into:
- 1 → Customer will make a transaction  
- 0 → Customer will not make a transaction  

---

## 🗂️ Dataset Description
- Domain: Banking  
- Total Features: 200 anonymized numerical features  
- Additional Columns:
  - `ID_code` – Unique customer identifier  
  - `target` – Transaction indicator (0 or 1)  

> Note: Since feature names are anonymized, detailed EDA is limited.

---

## ⚙️ Methodology
- Data loading and preprocessing  
- Handling high-dimensional feature space  
- Building multiple classification models  
- Model evaluation and comparison  
- Selecting the best model for production use  

---

## 🤖 Machine Learning Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting (if applicable)  

Model performance is evaluated using metrics such as accuracy, precision, recall, and ROC-AUC score.

---

## 📊 Results
- Compared multiple models to identify the best-performing classifier  
- Achieved reliable prediction performance despite anonymized features  
- Selected the optimal model based on evaluation metrics  

---

## ⚠️ Challenges Faced
- High-dimensional data with no feature descriptions  
- Risk of overfitting  
- Feature importance interpretation  

These challenges were addressed using proper model selection and evaluation techniques.

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 🚀 Conclusion
The project successfully predicts customer transaction behavior and demonstrates the application of machine learning in banking analytics to support data-driven decision-making.

---


