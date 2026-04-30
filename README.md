# 🏥 MaternaInsight — Maternal & Fetal Health Monitoring System

> An end-to-end Machine Learning-based clinical decision support system for maternal health risk assessment and fetal health classification, built using Python and Streamlit.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://maternainsight.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🔗 Live Demo
**[👉 Click here to open MaternaInsight](https://maternainsight.streamlit.app/)**

---

## 📌 Overview

MaternaInsight is a clinical decision support tool designed for healthcare professionals, nurses, and rural health workers. It provides:

- **Maternal Health Risk Prediction** — classifies pregnancy risk as Low, Mid, or High using 6 clinical parameters
- **Fetal Health Classification** — classifies fetal condition as Normal, Suspect, or Pathological using 21 CTG measurements
- **SHAP Explainability** — explains every prediction with feature contribution charts
- **System Performance Dashboard** — clinical reference guide and model evaluation metrics

---

## 🧠 Models

| Model | Algorithm | Accuracy | Macro F1 |
|-------|-----------|----------|----------|
| Maternal Health Risk | LightGBM + Optuna | 90.64% | 91.04% |
| Fetal Health Classification | Stacking Ensemble | 94.13% | 88.66% |

---

## 🖼️ Screenshots

| Home | Maternal Risk | Fetal Health |
|------|--------------|--------------|
| ![Home](screenshots/home.png) | ![Maternal](screenshots/maternal.png) | ![Fetal](screenshots/fetal.png) |

---

---

## ⚙️ Tech Stack

- **Frontend:** Streamlit, Plotly, streamlit-option-menu
- **ML Models:** LightGBM, XGBoost, Random Forest, Stacking Ensemble
- **Explainability:** SHAP (TreeExplainer + KernelExplainer)
- **Preprocessing:** Scikit-learn, SMOTETomek (imbalanced-learn)
- **Hyperparameter Tuning:** Optuna (100 trials)

---

## 📊 Datasets

| Dataset | Source | Records |
|---------|--------|---------|
| Maternal Health Risk | [UCI / Kaggle](https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data) | 1,014 |
| Fetal Health CTG | [UCI / Kaggle](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification) | 2,126 |

---

## 🚀 Run Locally

```bash
git clone https://github.com/YOUR_USERNAME/maternainsight.git
cd maternainsight
pip install -r requirements.txt
streamlit run app.py
```

---

## ⚠️ Disclaimer

MaternaInsight is a research-grade decision support tool. All predictions must be reviewed by a qualified healthcare professional. This system has not undergone clinical trial validation and is not approved for standalone diagnostic use.

---

## 👩‍💻 Developed By

| Name | 
|------|
| Archana S Shetty |
| Raksha Nandeesh |
| Bhuvana J |
| Sohan Anand |

**JSS Science and Technology University | Dept. of CS&E | Academic Year 2025–26**
