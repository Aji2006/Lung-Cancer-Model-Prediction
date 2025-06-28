# **Lung Cancer Prediction Model**

This project focuses on predicting the likelihood of lung cancer in patients using machine learning techniques applied to clinical and demographic data.

## 🧠 Objective
The goal is to:
  - Classify whether a patient is likely to have lung cancer
  - Identify important features that contribute to the prediction

## 📁 Dataset
The dataset typically includes patient medical and demographic information such as:
  - age : Patient's age
  - gender : Gender of the patient
  - cancer_stage : Stage of lung cancer (if diagnosed)
  - family_history : Whether the patient has a family history of cancer
  - smoking_status : Smoking habits (e.g., non-smoker, former smoker, current smoker)
  - bmi : Body Mass Index
  - cholesterol_level : Cholesterol levels in the blood
  - hypertension : Indicates if the patient has high blood pressure
  - asthma : Indicates if the patient has asthma
  - cirrhosis : Indicates if the patient has liver cirrhosis
  - other_cancer : History of other types of cancer
  - treatment_type : Type of treatment received (e.g., chemotherapy, surgery, radiation)

  > **Note**: All data used in this project must be anonymized and ethically sourced.

## 🛠️ Tools & Libraries
  - Python 3.12.8
  - Scikit-Learn
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - XGBoost (Classifier)

## ⚙️ Workflow
  1. **Data Preprocessing**
     - Categorical encoding
     - Feature scaling/normalization
     - PCA for Feature Extraction
  2. **Exploratory Data Analysis (EDA)**
     - Data distribution analysis
     - Feature correlation
     - Outlier detection
  3. **Model Development**
     - Train-test split
     - Training with models (XGBoost Classifier)
     - Evaluation metrics: Accuracy, Precision, Recall, F1-score
  4. **Model Interpretation**
     - Feature importance plots
  
   
