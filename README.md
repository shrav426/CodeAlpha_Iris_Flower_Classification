# 🌸 Iris Flower Classification

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-green.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-yellow.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-red.svg)](https://seaborn.pydata.org/)

---

## 🚀 Project Overview

Built a **production-ready Machine Learning classifier** that achieves **96% accuracy** in identifying Iris flower species. This project demonstrates end-to-end implementation of a supervised learning pipeline with comprehensive data analysis and model evaluation.

**Business Impact:** Can be extended to agricultural tech, botanical research, and automated plant identification systems.

---

## 💡 Key Achievements

| Achievement | Detail |
|-------------|--------|
| **Accuracy** | 96% on test data |
| **Precision/Recall** | 96% macro average |
| **False Positive Rate** | < 5% across all classes |
| **Inference Time** | < 0.1 seconds per prediction |
| **Code Quality** | Modular, documented, production-ready |

---

## 📊 Exploratory Data Analysis Insights

- Identified **strong correlation** between petal length and species classification
- Discovered that **Setosa** is completely separable from other species
- Used **pair plots & heatmaps** to visualize feature relationships
- Applied **feature scaling** to optimize model performance

---

## 🧠 Model Architecture
 
**Why Logistic Regression?**
- Baseline model with **excellent interpretability**
- Works well with **linearly separable data**
- Provides **feature importance** insights
- **Fast inference** suitable for production

---

## 📈 Performance Metrics (Detailed)

| Metric | Setosa | Versicolor | Virginica | Macro Avg |
|--------|--------|------------|-----------|-----------|
| **Precision** | 100% | 94% | 94% | 96% |
| **Recall** | 100% | 94% | 94% | 96% |
| **F1-Score** | 100% | 94% | 94% | 96% |

> Confusion Matrix: Only **2 misclassifications** out of 45 test samples

---

## 🔧 Tech Stack

| Category | Tools |
|----------|-------|
| **Language** | Python 3.8+ |
| **Environment** | Jupyter Notebook |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn (Logistic Regression, metrics) |
| **Version Control** | Git, GitHub |

---

## 📁 Repository Structure
├── data/
│ └── iris.csv
├── notebooks/
│ └── code_alpha_Iris_Flower_Classification.ipynb
├── src/
│ └── model.py
├── requirements.txt
├── README.md
└── LICENSE
