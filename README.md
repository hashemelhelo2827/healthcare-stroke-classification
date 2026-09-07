# Healthcare Stroke Classification

Machine learning pipeline for predicting stroke risk using clinical and demographic patient data.

## Overview

This project builds classification models to predict whether a patient is likely to suffer a stroke based on attributes such as age, gender, hypertension, heart disease, glucose level, BMI, and smoking status. Two models are compared: **Logistic Regression** and **Support Vector Machine (SVM)**.

## Dataset

The project uses the [Healthcare Stroke Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction) containing 5,110 patient records with the following features:

| Feature | Description |
|---------|-------------|
| `gender` | Male / Female / Other |
| `age` | Patient age |
| `hypertension` | 0 or 1 |
| `heart_disease` | 0 or 1 |
| `ever_married` | Yes / No |
| `work_type` | Private, Self-employed, Govt_job, etc. |
| `Residence_type` | Urban / Rural |
| `avg_glucose_level` | Average glucose level |
| `bmi` | Body mass index |
| `smoking_status` | formerly smoked, never smoked, smokes, Unknown |
| `stroke` | Target variable (0 or 1) |

## Tech Stack

- Python
- pandas / NumPy
- scikit-learn (Logistic Regression, SVM, preprocessing, metrics)
- seaborn / Matplotlib

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/hashemelhelo2827/healthcare-stroke-classification.git
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn seaborn matplotlib
   ```
3. Open the notebook:
   ```bash
   jupyter notebook "Task (1).ipynb"
   ```

## Contributors

- **Hashem Elhelo**
- **Poula Essam**
- **Youssef Mohamed Abd Elaziz**
