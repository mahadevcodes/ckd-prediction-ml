# 🩺 Chronic Kidney Disease Prediction using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Ensemble-success?style=for-the-badge)
![Gradio](https://img.shields.io/badge/Gradio-Web%20App-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

<p align="center">
<b>Hybrid Machine Learning Model for Early Chronic Kidney Disease Prediction using Ensemble Learning</b>
</p>

<p align="center">
A Machine Learning project that predicts Chronic Kidney Disease (CKD) using advanced preprocessing, feature engineering, SMOTE, and ensemble learning techniques.
</p>

---

# 🚀 Overview

Chronic Kidney Disease (CKD) is a serious health condition that can lead to kidney failure if not detected early.

This project applies Machine Learning techniques to predict CKD accurately using patient health parameters. The model includes:

- Data Cleaning
- Feature Engineering
- SMOTE Oversampling
- Ensemble Learning
- Interactive Prediction using Gradio

---

# ✨ Features

- 🧹 Data Preprocessing
- 📊 Exploratory Data Analysis
- ⚙️ Feature Engineering
- ⚖️ SMOTE for Class Balancing
- 🤖 Ensemble Machine Learning Model
- 📈 Model Evaluation
- 🌐 Interactive Gradio Interface
- 🎯 High Prediction Accuracy

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| XGBoost | Ensemble Learning |
| Imbalanced-Learn | SMOTE |
| Joblib | Model Serialization |
| Gradio | Web Interface |

---

# 📁 Dataset

The project uses a Chronic Kidney Disease dataset containing patient medical records.

### Features include

- Age
- Blood Pressure
- Specific Gravity
- Albumin
- Sugar
- Blood Glucose Random
- Blood Urea
- Serum Creatinine
- Sodium
- Potassium
- Hemoglobin
- Packed Cell Volume
- White Blood Cell Count
- Red Blood Cell Count
- Hypertension
- Diabetes Mellitus
- Coronary Artery Disease
- Appetite
- Pedal Edema
- Anemia

### Target

- CKD
- Not CKD

---

# 📂 Project Structure

```text
ckd-prediction-ml/
│
├── Chronic_Kidney_Disease_Prediction.ipynb
├── requirements.txt
├── LICENSE
└── README.md
```

---

# 📊 Machine Learning Pipeline

```text
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Feature Engineering
   │
   ▼
SMOTE Oversampling
   │
   ▼
Model Training
   │
   ▼
Ensemble Learning
   │
   ▼
Performance Evaluation
   │
   ▼
Gradio Prediction Interface
```

---

# 🧠 Machine Learning Models

The project evaluates multiple algorithms including:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- Hybrid Soft Voting Ensemble

The final prediction system uses a Hybrid Ensemble Model for improved accuracy and robustness.

---
## 📈 Model Performance

### Highlights

- ✅ Accuracy: 98.75%
- ✅ Precision: 100.00%
- ✅ Recall: 98.00%
- ✅ F1-Score: 98.99%
- ✅ ROC-AUC Score: 1.00
- ✅ Ensemble-based prediction using Hybrid Voting Model

| Metric | Value |
|---------|-------|
| Accuracy | 98.75% |
| Precision | 100.00% |
| Recall | 98.00% |
| F1 Score | 98.99% |
| ROC-AUC | 1.00 |

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/mahadevcodes/ckd-prediction-ml.git
```

Go inside the project

```bash
cd ckd-prediction-ml
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

Open the notebook

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

Run all cells to

- Load Dataset
- Train Models
- Evaluate Performance
- Launch Gradio Interface

---

# 📸 Project Screenshots

Project screenshots and prediction results will be added soon.

---

# 📋 Requirements

Main packages used:

- gradio
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- xgboost
- joblib

---

# 🗺 Roadmap

- 🚀 Deploy on Hugging Face Spaces
- 🌐 Deploy Web Version
- 📊 Add Explainable AI (SHAP/LIME)
- 🤖 Improve UI Design
- 📈 Train on larger healthcare datasets

---

# 👨‍💻 Author

**Mahadev Vengurlekar**

💼 Full Stack Developer

🤖 Automation Engineer

🧠 AI & Machine Learning Enthusiast

### Connect with me

- GitHub: https://github.com/mahadevcodes
- LinkedIn: https://www.linkedin.com/in/mahadev-vengurlekar

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

<p align="center">
Made with ❤️ by <b>Mahadev Vengurlekar</b>
</p>
