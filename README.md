# Disease Diagnosis Using Machine Learning

A comparative study of supervised machine learning algorithms for multi-class disease classification using patient demographics, reported symptoms, and clinical measurements.

## Overview

This project explores and compares different machine learning models to classify patients into five diagnostic categories:

- Healthy
- Cold
- Flu
- Bronchitis
- Pneumonia

The dataset contains **2,000 records and 13 features**, covering demographic information, symptoms, vital signs, diagnosis, severity, and treatment plan.

## Dataset

The dataset contains the following feature groups:

| Feature Group | Features |
|---|---|
| Demographics | Age, Gender |
| Symptoms | Symptom_1, Symptom_2, Symptom_3 |
| Clinical Measurements | Heart Rate, Body Temperature, Blood Pressure, Oxygen Saturation |
| Additional Attributes | Diagnosis, Severity, Treatment Plan |

### Diagnosis Distribution

| Diagnosis | Records |
|:---|---:|
| Healthy | 1,167 |
| Bronchitis | 334 |
| Flu | 292 |
| Cold | 163 |
| Pneumonia | 44 |
| **Total** | **2,000** |

The dataset has an imbalanced class distribution, with Pneumonia being the least represented class.

## Machine Learning Models

The project investigates the following algorithms:

1. Logistic Regression
2. Random Forest
3. XGBoost
4. LightGBM
5. Decision Tree
6. Support Vector Machine (SVM)
7. K-Nearest Neighbors (KNN)
8. Naive Bayes
9. Artificial Neural Network (ANN)

Several models are also evaluated with hyperparameter tuning to investigate potential improvements in performance.

## Project Workflow

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature encoding
3. Data normalization and outlier analysis
4. Feature correlation analysis
5. Model development and training
6. Hyperparameter tuning
7. Model evaluation and comparison
8. Performance visualization

## Evaluation

Model performance is assessed using multiple evaluation techniques:

- Accuracy
- Precision, Recall, and F1-score
- Confusion Matrices
- ROC Curves and AUC
- Cross-validation

## Results & Visualizations

The repository includes visualizations and supporting files generated during the analysis:

| File | Description |
|---|---|
| `corrected_roc_curves.png` | ROC curves for model comparison |
| `correlation_matrix.png` | Feature correlation matrix |
| `decision_tree.pdf` | Decision tree visualization |
| `feature_importance.png` | Feature importance visualization |
| `learning_curves.png` | Model learning curves |
| `model_performance1.csv` | Model performance results |

## Repository Structure

```text
disease-diagnosis-ml/
│
├── disease_diagnosis.ipynb
├── disease_diagnosis.csv
├── model_performance1.csv
│
├── corrected_roc_curves.png
├── correlation_matrix.png
├── feature_importance.png
├── learning_curves.png
│
├── .gitignore
└── README.md
```

## Technologies & Libraries

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost, LightGBM
- **Deep Learning:** TensorFlow / Keras
- **Scientific Computing:** SciPy
- **Environment:** Jupyter Notebook

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/aylin-nxt/disease-diagnosis-ml.git
cd disease-diagnosis-ml
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm tensorflow scipy jupyter
```

### 3. Launch the notebook

```bash
jupyter notebook disease_diagnosis.ipynb
```

## Disclaimer

This project is an academic machine learning experiment intended for educational and research purposes only. The dataset and model predictions are not clinically validated and must not be used for medical diagnosis or clinical decision-making.
