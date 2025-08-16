# StrokeGuard
Stroke Prediction Model
# Cerebral Stroke Prediction

This repository contains a dataset and a Jupyter Notebook for predicting cerebral stroke occurrence using machine learning techniques.  
The goal of this project is to analyze patient health records and develop a model that can assist in early detection of stroke risk.

---

## Repository Structure
- `Cereberal_Dataset.csv` — The dataset used for training and evaluation.
- `Cerebral_stroke.ipynb` — Jupyter Notebook containing data preprocessing, exploratory data analysis (EDA), and model building.
- `README.md` — Project documentation.
- `LICENSE` — License for open-source usage.

---

## Features
- Data Cleaning and Preprocessing  
- Exploratory Data Analysis (EDA) with visualizations  
- Feature selection and transformation  
- Machine Learning model training and evaluation  
- Stroke risk prediction  

---

## Technologies Used
- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## Models Used

The following machine learning models were implemented and compared:

- Logistic Regression 
- Decision Tree Classifier  
- Random Forest Classifier  
- XGBoost Classifier  

Performance metrics (Accuracy, Precision, Recall, F1-score, ROC-AUC) were used to evaluate the models and determine the most effective approach for stroke prediction.

## Dataset
The dataset includes patient information such as:
- Age  
- Gender  
- Hypertension  
- Heart Disease  
- Smoking Status  
- Other health indicators  

**Target Variable:** `stroke` (1 = Stroke, 0 = No Stroke)

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cerebral-stroke-prediction.git
   cd cerebral-stroke-prediction
