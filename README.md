# Wine-Quality-Prediction-ML
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/Tanishka-Rohilla/Wine-Quality-Prediction-ML/blob/main/Wine_Quality_Prediction.ipynb)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)


# 🍷 Wine Quality Prediction – End-to-End Machine Learning Project

---

## 📌 Project Overview

This project demonstrates a complete **end-to-end Machine Learning workflow** using a real-world dataset.

The goal is to predict wine quality based on its chemical properties and convert the multi-class problem into a **binary classification task (Good vs Bad Wine)**.

The project covers all major steps involved in building a real-world ML system, from data understanding to model evaluation.

---

## 🎯 Objective

- Understand and analyze the wine quality dataset  
- Perform data preprocessing and exploratory data analysis (EDA)  
- Convert the problem into a binary classification task  
- Train and compare multiple Machine Learning models  
- Optimize model performance using pipelines and hyperparameter tuning  

---

## 📊 Dataset Information

- **File Name:** `winequality.csv`  
- **Rows:** Each row represents one wine sample  
- **Columns:** Chemical properties of wine  
- **Target Column:** `quality`  

---

## 🔄 Binary Classification Rule

- **Quality ≥ 7** → Good Wine (1)  
- **Quality < 7** → Bad Wine (0)  

---

## 🛠️ Technologies Used

- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔍 Project Workflow

### 1️⃣ Data Loading & Understanding
- Load dataset using Pandas  
- Inspect structure using `head()`, `tail()`, and `shape`  

### 2️⃣ Data Inspection
- Check column names, data types, shape, and summary statistics  

### 3️⃣ Missing Value Analysis
- Verify missing values using `isnull()`  

### 4️⃣ Exploratory Data Analysis (EDA)
- Analyze wine quality distribution  
- Visualize quality scores using count plots  

### 5️⃣ Binary Classification Conversion
- Create `quality_label` column for Good/Bad classification  

### 6️⃣ Feature & Target Separation
- Separate input features (X) and target variable (y)  

### 7️⃣ Train-Test Split
- Split data into training and testing sets  

### 8️⃣ Feature Scaling
- Apply `StandardScaler` for feature normalization  

---

## 🔢 Pipeline & Hyperparameter Tuning

- Create ML pipeline  
- Apply `GridSearchCV` for parameter tuning  

---

## 📈 Results

- Random forest and SVM models performed better due to their ability to handle complex patterns  
- Feature scaling improved performance for distance-based models  
- Hyperparameter tuning helped achieve optimal model accuracy  

---

## ✅ Key Learnings

- Importance of data preprocessing and EDA  
- Handling classification problems in real-world ML systems  
- Comparing multiple ML models  
- Improving performance through hyperparameter tuning  

---

## 🚀 Conclusion

This project reflects a **real-world Machine Learning application** where data understanding, preprocessing, model selection, and evaluation are equally important.

It provides a strong foundation for building **production-ready ML systems**.

---

## 📂 How to Run the Project

### Option 1: Run on Google Colab (Recommended)
1. Click the **Open in Colab** badge above  
2. Upload `winequality.csv` when prompted  
3. Run all cells sequentially  

### Option 2: Run Locally
1. Clone the repository  
2. Open the Jupyter Notebook  
3. Install required libraries  
4. Run all cells step-by-step  
 

---

## 👤 Author

**Tanishka**
