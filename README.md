\# Disease Diagnosis Using Machine Learning



A multi-class classification project exploring supervised machine learning models for disease diagnosis based on patient demographics, reported symptoms, and clinical measurements.



\## Project Overview



This project investigates and compares multiple machine learning approaches for classifying patients into five diagnostic categories:



\- Healthy

\- Cold

\- Flu

\- Bronchitis

\- Pneumonia



The dataset contains \*\*2,000 records and 13 columns\*\*, including demographic information, symptoms, vital signs, diagnosis, severity, and treatment plan.



\## Dataset



The dataset includes the following types of information:



\- \*\*Demographic features:\*\* Age, Gender

\- \*\*Symptoms:\*\* Symptom\_1, Symptom\_2, Symptom\_3

\- \*\*Clinical measurements:\*\* Heart rate, Body temperature, Blood pressure, Oxygen saturation

\- \*\*Additional attributes:\*\* Diagnosis, Severity, Treatment plan



\### Diagnosis Distribution



| Diagnosis | Number of Records |

|---|---:|

| Healthy | 1,167 |

| Bronchitis | 334 |

| Flu | 292 |

| Cold | 163 |

| Pneumonia | 44 |

| \*\*Total\*\* | \*\*2,000\*\* |



The dataset has an imbalanced class distribution, particularly for Pneumonia.



\## Machine Learning Models



The project explores and compares the following algorithms:



1\. Logistic Regression

2\. Random Forest

3\. XGBoost

4\. LightGBM

5\. Decision Tree

6\. Support Vector Machine (SVM)

7\. K-Nearest Neighbors (KNN)

8\. Naive Bayes

9\. Artificial Neural Network (ANN)



Hyperparameter tuning is performed for several models to investigate potential improvements in predictive performance.



\## Project Workflow



1\. Exploratory Data Analysis (EDA)

2\. Data preprocessing and feature encoding

3\. Data normalization and outlier analysis

4\. Feature correlation analysis

5\. Model development and training

6\. Hyperparameter tuning

7\. Model evaluation and comparison

8\. Visualization of model performance



\## Evaluation Metrics



Models are evaluated using:



\- Accuracy

\- Precision

\- Recall

\- F1-score

\- ROC curves and AUC

\- Confusion matrices

\- Cross-validation



\## Repository Structure



```text

disease-diagnosis-ml/

│

├── disease\_diagnosis.ipynb

├── disease\_diagnosis.csv

├── model\_performance1.csv

│

├── corrected\_roc\_curves.png

├── correlation\_matrix.png

├── decision\_tree.pdf

├── feature\_importance.png

├── learning\_curves.png

│

├── .gitignore

└── README.md

```



\## Technologies \& Libraries



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- XGBoost

\- LightGBM

\- TensorFlow / Keras

\- SciPy

\- Jupyter Notebook



\## How to Run



1\. Clone the repository:



```bash

git clone https://github.com/aylin-nxt/disease-diagnosis-ml.git

```



2\. Navigate to the project directory:



```bash

cd disease-diagnosis-ml

```



3\. Install the required libraries:



```bash

pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm tensorflow scipy jupyter

```



4\. Launch Jupyter Notebook:



```bash

jupyter notebook disease\_diagnosis.ipynb

```



\## Disclaimer



This project is an academic machine learning experiment. Its dataset and predictions are intended for educational and research purposes only and must not be used for medical diagnosis or clinical decision-making.

