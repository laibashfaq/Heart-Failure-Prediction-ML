# Heart Failure Prediction using Machine Learning

## Overview

This project focuses on predicting the likelihood of heart disease using Machine Learning techniques. The notebook performs complete data analysis, preprocessing, visualization, feature engineering, model training, and evaluation on a heart disease dataset.

The goal of this project is to build a predictive model that can help identify patients at risk of heart disease based on medical attributes.

---

# Dataset Information

The dataset used in this project contains several medical features related to heart health.

### Features Included

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise Induced Angina
* Oldpeak
* ST Slope
* HeartDisease (Target Variable)

### Target Variable

* `0` → No Heart Disease
* `1` → Heart Disease Present

---

# Project Workflow

The notebook follows these major steps:

## 1. Data Loading

* Loads the dataset using Pandas.
* Displays dataset structure and sample records.

## 2. Data Exploration

* Checks:

  * Dataset shape
  * Column information
  * Missing values
  * Statistical summary

## 3. Data Preprocessing

* Handles categorical and numerical features.
* Uses Label Encoding for categorical columns.
* Prepares the dataset for machine learning models.

## 4. Exploratory Data Analysis (EDA)

* Visualizes:

  * Distribution of categorical features
  * Numerical feature analysis
  * Correlation between variables
  * Heart disease trends

## 5. Feature Engineering

* Separates input features and target labels.
* Splits data into training and testing sets.

## 6. Model Training

The notebook trains Machine Learning models to predict heart disease.

Possible models used include:

* Logistic Regression
* Random Forest
* Decision Tree
* K-Nearest Neighbors
* Support Vector Machine

## 7. Model Evaluation

The trained models are evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Performance Comparison

---

# Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/heart-failure-prediction.git
```

## Navigate to the Project Folder

```bash
cd heart-failure-prediction
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Project

Open the notebook using Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```bash
heart_failure_prediction.ipynb
```

---

# Project Structure

```text
heart-failure-prediction/
│
├── heart_failure_prediction.ipynb
├── heart.csv
├── README.md
└── requirements.txt
```

---

# Results

The project successfully analyzes heart disease data and builds predictive machine learning models capable of identifying patients with potential heart disease risks.

The visualizations and evaluation metrics help compare model performance and understand important medical features contributing to predictions.

---

# Future Improvements

* Hyperparameter tuning
* Deployment using Flask or Streamlit
* Deep Learning implementation
* Real-time prediction system
* Improved feature engineering

---

# Author

Developed as a Machine Learning project for educational and analytical purposes.

---

# License

This project is open-source and available for learning and educational use.
