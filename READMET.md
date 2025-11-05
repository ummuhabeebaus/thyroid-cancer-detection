# 🩺 Thyroid Cancer Recurrence Detection

## 📌 Overview
This project predicts the likelihood of thyroid cancer recurrence using patient medical data.  
It demonstrates a complete **machine learning pipeline** — from raw data to a deployed model — aimed at assisting early detection of high-risk cases.

---

## 📊 Dataset
- **Records:** 383 patients  
- **Target Variable:** `Recurred` (0 = No Recurrence, 1 = Recurrence)  
- **Features:** Age, Gender, Smoking History, Radiotherapy History, Thyroid Function, Pathology, Tumor Stage, etc.  
- **Type:** Combination of numerical and categorical features  

---

## ⚙️ Workflow
1. **Data Loading & Exploration** — Check structure, types, missing values  
2. **Data Cleaning & Preprocessing** — Handle nulls, encode categorical values, save cleaned dataset  
3. **Exploratory Data Analysis (EDA)** — Visualize feature distributions, correlations, and class balance  
4. **Model Training & Comparison** — Logistic Regression, KNN, Decision Tree, Random Forest  
5. **Model Selection** — Random Forest chosen for highest accuracy & recall  
6. **Final Model Deployment** — Save as `thyroid_recurrence_model.pkl` and predict for new patients (manual or CSV input)

---

## 📈 Results
- **Best Model:** Random Forest Classifier  
- **Reason:** Highest recall for recurrence cases (critical in medical prediction)  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Joblib  
- **Environment:** Google Colab / Jupyter Notebook  

---


# 🚀 How to Run
```bash
1. Open the notebook in Google Colab or Jupyter.  
2. Upload the dataset file.  
3. Run all steps from data loading to model evaluation.  
4. Use the saved model (`thyroid_recurrence_model.pkl`) for manual predictions.





