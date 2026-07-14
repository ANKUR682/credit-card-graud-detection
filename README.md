# credit-card-graud-detection

# 💳 Credit Card Fraud Detection

A Machine Learning project that detects fraudulent credit card transactions using multiple classification algorithms and identifies the best-performing model based on evaluation metrics.

---

## 📌 Project Overview

Credit card fraud has become a major challenge in digital payments. This project analyzes real-world transaction data, performs data preprocessing and exploratory data analysis (EDA), trains multiple machine learning models, and compares their performance to accurately detect fraudulent transactions.

---

## 🚀 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Handling highly imbalanced dataset
- Feature scaling
- Model training using multiple algorithms
- Model evaluation using standard classification metrics
- Saved trained model for future predictions

---

## 📂 Project Structure

```
├── creditcard.ipynb          # Complete Jupyter Notebook
├── credit_card_model.pkl     # Trained Machine Learning Model
├── output.html               # Notebook exported as HTML
├── .gitignore
└── README.md
```

---

## 📊 Dataset

- **Dataset:** Credit Card Fraud Detection Dataset
- **Source:** Kaggle
- **Transactions:** 284,807
- **Fraud Cases:** 492
- **Fraud Percentage:** 0.172%

> The dataset is not included in this repository because it exceeds GitHub's file size limit.

Download it from:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Place the downloaded `creditcard.csv` file in the project directory before running the notebook.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Jupyter Notebook

---

## 📈 Machine Learning Models

The following algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

## 🏆 Best Model

After comparing all models, **XGBoost** achieved the best performance with excellent Precision, Recall, and F1-Score on the highly imbalanced dataset.

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/ANKUR682/credit-card-graud-detection.git
```

### Move into the project directory

```bash
cd credit-card-graud-detection
```

### Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost joblib
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
creditcard.ipynb
```

---

## 📸 Project Workflow

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
EDA
    │
    ▼
Feature Scaling
    │
    ▼
Model Training
    │
    ▼
Performance Comparison
    │
    ▼
Best Model Selection
    │
    ▼
Saved Model (.pkl)
```

---

## 📌 Future Improvements

- Deploy using Streamlit
- Build a REST API using Flask/FastAPI
- Hyperparameter optimization
- Real-time fraud prediction dashboard

---

## 👨‍💻 Author

**Ankur Singh**

- IIT Kharagpur
- Electrical Engineering

GitHub:
https://github.com/ANKUR682

---

## ⭐ If you found this project useful, consider giving it a star!
