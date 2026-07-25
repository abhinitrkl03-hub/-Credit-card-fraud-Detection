# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning algorithms. Since fraud detection is a highly imbalanced classification problem, the project applies data preprocessing, feature scaling, SMOTE oversampling, and multiple ML models to identify fraudulent transactions with high accuracy.

---

## 🚀 Features
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib and Seaborn
- Handling class imbalance using SMOTE
- Feature scaling using StandardScaler
- Model training and evaluation
- Hyperparameter tuning using RandomizedSearchCV
- Performance comparison of multiple machine learning models

---

## 📂 Dataset
The project uses the **Credit Card Fraud Detection Dataset**, which contains anonymized transaction features.

**Dataset Features**
- Time
- Amount
- V1 – V28 (PCA transformed features)
- Class
  - 0 → Genuine Transaction
  - 1 → Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Plotly

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Dataset information
- Missing value analysis
- Class distribution
- Transaction amount distribution
- Transaction time distribution
- Correlation heatmap
- Time vs Amount visualization

---

## ⚙️ Data Preprocessing

- Removed target column from features
- Train-test split
- Standardization using StandardScaler
- Handled class imbalance using SMOTE

---

## 🤖 Machine Learning Models

The following models were implemented:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## 🔍 Hyperparameter Tuning

Random Forest was optimized using:

- RandomizedSearchCV
- Cross Validation
- F1 Score as evaluation metric

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix
- Cross Validation Score

---

## 📁 Project Structure

```
CreditCardFraudDetection/
│
├── CREDITCARDFRAUD.ipynb
├── creditcard.csv
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/CreditCardFraudDetection.git
```

Go to the project folder

```bash
cd CreditCardFraudDetection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

Open

```
CREDITCARDFRAUD.ipynb
```

---

## 📌 Future Improvements

- Deep Learning (Neural Networks)
- LightGBM and CatBoost implementation
- Explainable AI using SHAP
- Real-time fraud detection API
- Model deployment using Streamlit or Flask

---

## 📄 License

This project is developed for educational and learning purposes.

---


