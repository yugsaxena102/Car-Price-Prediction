# 🚗 Car Price Prediction using Machine Learning

Predict the selling price of used Ford cars using Machine Learning by applying data preprocessing, exploratory data analysis (EDA), feature engineering, feature encoding, feature scaling, and regression modeling.

---

## 📌 Project Overview

The goal of this project is to build a Machine Learning model capable of predicting the price of used cars based on their specifications.

The project demonstrates an end-to-end machine learning workflow—from raw data preprocessing to model evaluation.

---

## 🎯 Objectives

* Perform data preprocessing and cleaning
* Analyze relationships between features using EDA
* Engineer and transform features for better model performance
* Encode categorical variables
* Scale numerical features
* Train and evaluate a regression model
* Predict used car prices accurately

---

## 📂 Dataset

**Dataset:** `ford.csv`

### Features

| Feature      | Description          |
| ------------ | -------------------- |
| Model        | Car model            |
| Year         | Manufacturing year   |
| Transmission | Transmission type    |
| Mileage      | Distance driven      |
| Fuel Type    | Petrol/Diesel/Hybrid |
| Tax          | Road tax             |
| MPG          | Miles per gallon     |
| Engine Size  | Engine capacity      |
| Price        | Target variable      |

---

# 🛠️ Tech Stack

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📊 Project Workflow

```text
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis (EDA)
   │
   ▼
Feature Engineering
   │
   ▼
Label Encoding
   │
   ▼
One-Hot Encoding
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Prediction
   │
   ▼
Model Evaluation
```

---

# 🔍 Exploratory Data Analysis (EDA)

Performed:

* Dataset inspection
* Missing value analysis
* Duplicate record checking
* Correlation Heatmap
* Distribution plots
* Count plots
* Feature relationship analysis

---

# ⚙️ Feature Engineering

Implemented several preprocessing techniques:

* Selected relevant features
* Separated numerical and categorical columns
* Prepared input features (X) and target variable (y)

---

# 🔤 Feature Encoding

### Label Encoding

Used Label Encoding to convert categorical values into numerical labels where appropriate.

### One-Hot Encoding

Applied One-Hot Encoding for categorical features including:

* Model
* Transmission
* Fuel Type

This prevents the model from assuming an ordinal relationship among categories.

---

# 📈 Feature Scaling

Used **StandardScaler** to normalize numerical features such as:

* Year
* Mileage
* Tax
* MPG
* Engine Size

Feature scaling helps improve model training and convergence.

---

# 🤖 Machine Learning

The dataset was divided into training and testing sets using **Train-Test Split**.

The regression model was trained to predict the selling price of used cars using engineered features.

---

# 📊 Model Evaluation

Model performance was evaluated using regression metrics such as:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

# 📁 Project Structure

```text
Car-Price-Prediction/
│
├── carpriceml.ipynb
├── ford.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yugsaxena102/Car-Price-Prediction.git
```

Move into the project directory

```bash
cd Car-Price-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **carpriceml.ipynb** and run all cells.

---

# 🚀 Future Improvements

* Hyperparameter tuning
* Compare multiple regression algorithms
* Deploy using Flask or FastAPI
* Build an interactive web application
* Save the trained model using Pickle or Joblib

---
GitHub: https://github.com/yugsaxena102
---







