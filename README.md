# 🩺 Early-Stage Diabetes Risk Prediction (AI Project)

This project predicts **early-stage diabetes risk** based on non-invasive health indicators using **Machine Learning algorithms**. It uses symptoms and demographic data to classify individuals as **at risk** or **not at risk** of developing diabetes.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Model Performance](#model-performance)
- [Installation & Usage](#installation--usage)
- [Results](#results)
- [Future Scope](#future-scope)
- [Contributors](#contributors)

---

## ✅ Overview
The goal of this project is to **predict diabetes risk at an early stage** using **symptom-based features** and **demographic details**. Early detection helps in timely intervention, preventing complications and reducing healthcare costs.

We implemented and compared three models:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest** *(Best performer)*

---

## ✅ Problem Statement
Diabetes affects millions globally. Traditional diagnosis often occurs after disease progression. We need **non-invasive, accurate, and early prediction tools** for preventive healthcare.

---

## ✅ Dataset
- **Source:** [UCI Repository – Early Stage Diabetes Risk Prediction Dataset](https://archive.ics.uci.edu/dataset/529/early+stage+diabetes+risk+prediction+dataset)
- **Features:** 16 attributes (Age, Gender, Polyuria, Polydipsia, Sudden weight loss, etc.)
- **Target:** Diabetes risk (Positive/Negative)

---

## ✅ Features
- **Binary classification** (Positive or Negative risk)
- **Data preprocessing** (Encoding, cleaning, splitting)
- **Model comparison** with metrics: Accuracy, Precision, Recall, F1-Score
- **Cross-validation** for stability
- **Visualization**: Confusion Matrix, ROC Curve, Heatmaps

---

## ✅ Technologies Used
- **Python 3**
- **Pandas, NumPy** – Data Handling
- **Scikit-learn** – ML Models & Evaluation
- **Matplotlib, Seaborn** – Visualizations
- **Jupyter Notebook / Google Colab**

---

## ✅ Methodology
1. Data Cleaning & Preprocessing
2. Train-Test Split (70%-30%)
3. Model Building:
   - Logistic Regression
   - Decision Tree
   - Random Forest
4. Cross-Validation
5. Performance Evaluation & Visualization

---

## ✅ Model Performance
| Model              | Accuracy | AUC   |
|--------------------|---------|-------|
| Logistic Regression| 94%     | 0.97  |
| Decision Tree      | 97%     | 0.97  |
| **Random Forest**  | **98%** | 0.99  |

---

## ✅ Installation & Usage
Clone the repository:
```bash
git clone https://github.com/your-username/diabetes-risk-prediction.git
cd diabetes-risk-prediction
