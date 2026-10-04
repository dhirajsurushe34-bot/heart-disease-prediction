# Heart Disease Prediction System

An end-to-end Machine Learning web application designed to predict the likelihood of heart disease based on patient clinical parameters. This project aims to support early diagnosis and assist healthcare workflows by providing fast, data-driven cardiac risk assessments.

---

## 📌 Project Overview
Cardiovascular diseases are among the leading causes of mortality worldwide. Early detection plays a vital role in preventing severe complications. This system analyzes patient health metrics (such as age, cholesterol levels, resting blood pressure, and ECG results) to predict cardiac risk using supervised machine learning algorithms.

---

## 🚀 Key Features
* **Risk Assessment:** Evaluates multi-parameter clinical data to identify high-risk cardiovascular indicators.
* **Trained ML Models:** Evaluated on benchmark medical datasets using classification models (Logistic Regression, Random Forest, Decision Tree).
* **Interactive Interface:** Clean web UI (Streamlit / Flask) for rapid parameter input and visual risk feedback.
* **Preprocessed Pipeline:** Handles missing values, feature scaling, and categorical encoding.

---

## 📊 Dataset & Features
The model is trained using clinical attributes commonly found in datasets like the **UCI Heart Disease Dataset**:

* `age`: Age in years
* `sex`: Sex (1 = male, 0 = female)
* `cp`: Chest pain type (0 to 3)
* `trestbps`: Resting blood pressure (mm Hg)
* `chol`: Serum cholesterol (mg/dl)
* `fbs`: Fasting blood sugar (> 120 mg/dl: 1, else: 0)
* `restecg`: Resting electrocardiographic results
* `thalach`: Maximum heart rate achieved
* `exang`: Exercise-induced angina (1 = yes, 0 = no)
* `oldpeak`: ST depression induced by exercise relative to rest
* `slope`: Slope of the peak exercise ST segment
* `ca`: Number of major vessels colored by flouroscopy
* `thal`: Thalassemia defect type
* `target`: Diagnosis of heart disease (1 = presence, 0 = absence)

---

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning & Data Processing:** Scikit-Learn, Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Interface / Framework:** Streamlit / Flask

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/dhirajsurushe34-bot/heart-disease-prediction.git](https://github.com/dhirajsurushe34-bot/heart-disease-prediction.git)
   cd heart-disease-prediction

---
2. **Install required dependencies:**
   ```bash
   [pip install -r requirements.txt]


---
3. **Run the application:**
    ```bash
    streamlit run app.py
   # OR for Flask:
    # python app.py
    
---

# ⚠️ Disclaimer:
This tool is developed for educational and academic mini-project purposes and should not be used as a substitute for professional medical advice, diagnosis, or treatment.


