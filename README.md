# Graduation-Project
# 🩺 Early Prediction of Diabetes Risk Using Explainable Artificial Intelligence (XAI)

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-green)
![SHAP](https://img.shields.io/badge/SHAP-XAI-orange)
![Healthcare](https://img.shields.io/badge/Domain-Healthcare-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📖 Introduction

Diabetes Mellitus is one of the most significant public health challenges worldwide, particularly in Saudi Arabia. Early identification of high-risk individuals can reduce complications and improve preventive healthcare outcomes.

This project introduces an Explainable Artificial Intelligence (XAI) framework that combines the predictive power of XGBoost with the transparency of SHAP (SHapley Additive exPlanations) to deliver accurate and interpretable diabetes risk predictions.

Unlike traditional black-box machine learning models, our approach enables healthcare professionals to understand why a prediction was made, increasing trust, transparency, and clinical usability.

---

## 🎯 Project Objectives

* Develop a reliable diabetes risk prediction system.
* Detect high-risk individuals at an early stage.
* Improve model transparency using Explainable AI.
* Support healthcare professionals with interpretable predictions.
* Reduce missed diabetes cases through sensitivity-focused optimization.

---

## 🏗️ System Architecture

```text
Raw Dataset
     │
     ▼
Data Preprocessing
     │
     ▼
Feature Engineering
     │
     ▼
XGBoost Model
     │
     ▼
Performance Evaluation
     │
     ▼
SHAP Explainability Layer
     │
     ▼
Risk Prediction + Explanation
```

---

## 🚀 Key Features

✅ Early diabetes risk prediction

✅ Explainable AI using SHAP

✅ XGBoost-based predictive engine

✅ Global feature importance analysis

✅ Individual patient-level explanations

✅ Clinically-oriented decision support

✅ Transparent and interpretable predictions

---

## 🛠️ Technologies Used

| Category                | Technology       |
| ----------------------- | ---------------- |
| Programming             | Python           |
| Machine Learning        | XGBoost          |
| Explainable AI          | SHAP             |
| Data Processing         | Pandas, NumPy    |
| Model Evaluation        | Scikit-Learn     |
| Visualization           | Matplotlib       |
| Development Environment | Jupyter Notebook |

---

## 📊 Dataset Information

The study utilizes a validated Saudi diabetes dataset collected from the Western Region of Saudi Arabia.

### Dataset Statistics

| Item               | Value         |
| ------------------ | ------------- |
| Total Samples      | 4,896         |
| Diabetic Cases     | 990           |
| Non-Diabetic Cases | 3,906         |
| Target Variable    | Diabetes Risk |

### Features

* Age
* Gender
* BMI
* Waist Size
* Physical Activity
* Diet Habits
* Smoking Status
* Hypertension Medication
* Family History of Diabetes

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Data cleaning
* Feature selection
* Encoding categorical variables
* Dataset preparation

### 2. Data Splitting

* Training Set: 70%
* Validation Set: 15%
* Testing Set: 15%

### 3. Model Development

The prediction engine was built using XGBoost and optimized to prioritize patient safety through sensitivity-focused learning.

### 4. Explainability Integration

SHAP was integrated to provide:

* Global explanations
* Local patient explanations
* Feature contribution analysis

---

## 📈 Performance Results

| Metric               | Score  |
| -------------------- | ------ |
| Recall (Sensitivity) | 96.41% |
| Accuracy             | 81.13% |
| F1-Score             | 83.62% |
| AUC Score            | 88.21% |

### Clinical Impact

The model was specifically optimized to minimize False Negatives, ensuring that potentially diabetic patients are identified and referred for further medical evaluation.

---

## 🔍 Explainable AI (XAI)

### Global Explainability

Provides population-level insights by ranking the most influential diabetes risk factors.

### Local Explainability

Generates patient-specific explanations showing how each feature contributes to the final prediction.

This allows healthcare professionals to understand:

* Why a patient was classified as high risk.
* Which factors increased the prediction score.
* Which factors reduced the prediction score.

---

## 📂 Repository Structure

```text
Graduation-Project/
│
│
├── notebooks/
│   └── GP_code.ipynb
│
│
├── results/
│   ├── shap_global.png
│   ├── shap_local.png
│   └── evaluation_metrics.png
│
├── report/
│   └── Diabetes_Prediction_XAI.pdf
│
└── README.md
```

---

## 💡 Future Enhancements

* Real-time clinical deployment
* Web-based prediction dashboard
* Integration with Electronic Health Records (EHR)
* Deep Learning model comparison
* Mobile healthcare application
* External clinical validation

---

## 👨‍💻 Team Members

* Abdullah Altuwaijri
* Abdulmajeed Abalkhail
* Fahad Alharbi
* Abdulmohsen Aleid

### Academic Supervisor

Dr. Manal Alghaith

---

## ⚠️ Disclaimer

This project is intended for educational and research purposes only. It should be used as a clinical decision-support tool and not as a replacement for professional medical diagnosis or healthcare consultation.

---

## 📜 License

This project is licensed under the MIT License.

