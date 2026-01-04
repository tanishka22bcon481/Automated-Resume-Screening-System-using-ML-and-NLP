# Automated-Resume-Screening-System-using-ML-and-NLP
## 📌 Project Overview
This project automates the process of resume screening by classifying resumes into predefined job categories using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
It aims to reduce manual effort in resume shortlisting and improve efficiency in the recruitment process.

---

## 🚀 Features
- Cleaning and preprocessing of unstructured resume text  
- Conversion of text data into numerical form using **TF-IDF vectorization**  
- Multi-class classification of resumes into job roles  
- Prediction of job category for new/unseen resumes  

---

## 🧠 Problem Statement
Recruiters often spend significant time manually screening resumes.  
This project solves that problem by building an **automated resume screening system** that can classify resumes based on their content.

**Problem Type:** Multi-class text classification using NLP.

---

## 📂 Dataset
- **Source:** Kaggle Resume Screening Dataset  
- **File:** `Resume Screening.csv`

### Dataset Columns:
- `Category` → Job category (target label)  
- `Resume` → Raw resume text  

The dataset contains resumes from multiple domains such as:
- Data Science  
- Java Developer  
- HR  
- Testing  
- DevOps  
- Mechanical Engineer, etc.

---

## 🛠 Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
- **Concepts:**  
  - Natural Language Processing (NLP)  
  - TF-IDF Vectorization  
  - Machine Learning (Classification)

---

## 🔄 Project Workflow
1. Load and explore the resume dataset  
2. Clean and preprocess resume text (remove noise, symbols, numbers, stopwords)  
3. Convert text into numerical features using **TF-IDF**  
4. Split data into training and testing sets  
5. Train a **Logistic Regression** classifier  
6. Evaluate model performance using accuracy and classification metrics  
7. Predict job category for new resume inputs  

---

## 📊 Model Used
- **Logistic Regression** (Multi-class Classification)

The model learns patterns in resume text and maps them to corresponding job categories.

---

## ✅ Results
- Successfully classified resumes into multiple job categories  
- Achieved good accuracy across different classes  
- Demonstrated effective handling of real-world unstructured text data  

---

## 🧪 Sample Prediction
**Input Resume Text:**
```text
Skills: Python, Machine Learning, SQL, Pandas, NumPy  
Experience: Data analysis, model building, visualization
