# 🚗 Car Price Prediction using Machine Learning

## 📖 Overview

This project predicts the selling price of used Ford cars using Machine Learning. It demonstrates the complete ML workflow, including data preprocessing, feature engineering, exploratory data analysis (EDA), feature encoding, model training, and performance evaluation.

---

# 🎯 Objectives

* Analyze a real-world used car dataset.
* Clean and preprocess the data.
* Perform Exploratory Data Analysis (EDA).
* Apply Feature Engineering techniques.
* Convert categorical variables into numerical form.
* Train and evaluate Machine Learning regression models.
* Predict the selling price of used cars accurately.

---

# 📂 Dataset

**Dataset:** `ford.csv`

### Features

* Model
* Year
* Transmission
* Mileage
* Fuel Type
* Tax
* MPG
* Engine Size
* Price (Target Variable)

---

# 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📊 Project Workflow

### 1. Data Collection

* Import Ford car dataset.

### 2. Data Exploration

* Display dataset information
* Check data types
* Analyze missing values
* Generate summary statistics

### 3. Data Cleaning

* Handle duplicate records
* Verify missing values
* Prepare dataset for modeling

### 4. Exploratory Data Analysis (EDA)

* Distribution plots
* Count plots
* Correlation Heatmap
* Pair plots
* Price distribution analysis

### 5. Feature Engineering

* Select relevant features
* Separate numerical and categorical columns
* Prepare input and target variables

### 6. Label Encoding

Applied Label Encoding where appropriate to convert categorical values into numerical representations.

### 7. One-Hot Encoding

Used One-Hot Encoding to transform categorical features such as:

* Model
* Transmission
* Fuel Type

This prevents the model from assuming an ordinal relationship between categories.

### 8. Feature Scaling

Standardized numerical features using **StandardScaler** to improve model performance.

Scaled features include:

* Year
* Mileage
* Tax
* MPG
* Engine Size

### 9. Train-Test Split

Split the dataset into training and testing sets using Scikit-learn.

### 10. Model Training

Trained a Machine Learning regression model to predict car prices.

### 11. Model Evaluation

Evaluated model performance using regression metrics and prediction analysis.

---

# 📁 Project Structure

```text
Car-Price-Prediction/
│
├── carpriceml.ipynb
├── ford.csv
├── README.md
└── requirements.txt
```

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yugsaxena102/Car-Price-Prediction.git
```

Move into the project directory:

```bash
cd Car-Price-Prediction
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `carpriceml.ipynb` and run all cells.

---

# 📈 Machine Learning Pipeline

```
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
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
Performance Evaluation
```

---

# 🚀 Future Improvements

* Compare multiple regression algorithms
* Perform Hyperparameter Tuning
* Build a prediction web app using Flask or FastAPI
* Deploy the model on the cloud
* Add model persistence using Pickle or Joblib





