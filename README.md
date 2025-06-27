# 🧠 DiabML: Diabetes Prediction Web App

This is a web-based machine learning application designed to predict diabetes conditions using clinical data. It classifies patients into:

- **Non-Diabetic**
- **Pre-Diabetic**
- **Diabetic**

---

## 💡 Why This Project?

Diabetes is a chronic and increasingly prevalent condition worldwide. Early prediction helps with timely intervention, lifestyle adjustments, and treatment — ultimately improving patient outcomes.

This application offers:

- ✅ A **simple, web-based tool** for healthcare professionals or patients to assess diabetes risk.  
- ✅ **Instant predictions** powered by machine learning models using clinically relevant indicators.  
- ✅ **Comparison of multiple ML models** to ensure reliable decision-making.

---

## 📌 Why These Features?

The chosen features are **biomarkers commonly used in clinical diagnostics** of diabetes and metabolic health:

| Feature | Why It’s Important |
|--------|---------------------|
| AGE | Diabetes risk increases with age |
| Gender | Influences metabolic rates and hormone levels |
| HbA1c | Key marker for average blood glucose levels |
| Urea, Cr | Indicators of kidney function (often affected by diabetes) |
| Chol, TG, HDL, LDL, VLDL | Lipid profile markers linked to metabolic syndrome |
| BMI | High BMI is correlated with insulin resistance and obesity |

These features were selected based on **medical literature**, **clinical relevance**, and **availability in real-world datasets**. They give a well-rounded view of a patient's metabolic and physiological status — crucial for accurate predictions.

---

## 📊 Dataset Details

The model was trained on a dataset with the following columns:

| Column | Description |
|--------|-------------|
| ID | Unique patient ID |
| No_Pation | Patient number |
| Gender | Male/Female |
| AGE | Patient age |
| Urea | Blood urea level |
| Cr | Creatinine |
| HbA1c | Glycated hemoglobin |
| Chol | Cholesterol |
| TG | Triglycerides |
| HDL | High-density lipoprotein |
| LDL | Low-density lipoprotein |
| VLDL | Very low-density lipoprotein |
| BMI | Body Mass Index |
| CLASS | Target label (0: Non-Diabetic, 1: Pre-Diabetic, 2: Diabetic) |

---

## 🚀 Key Features

- Interactive form to input patient health parameters  
- Preprocessing: scaling and PCA transformation before prediction  
- Predicts using three models:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Stacking Ensemble  
- Automatically selects the **best-performing model**  
- Visual output: **prediction result** and **model comparison graph**

---




