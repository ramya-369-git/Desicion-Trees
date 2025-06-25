# Decision Tree Classification on Credit Card Dataset

## 📋 Overview

This project applies a **Decision Tree Classifier** to detect potential credit card fraud based on transaction data. The model is trained on a dataset containing anonymized features that represent transaction behaviors, aiming to classify transactions as either legitimate or fraudulent.

---

## 🎯 Objectives

- Build a classification model using the **Decision Tree algorithm**.
- Identify fraudulent transactions from normal ones.
- Preprocess the data, handle class imbalance, and evaluate the model effectively.
- Visualize decision tree structure and analyze feature importance.

---

## 📊 Dataset

The dataset consists of European credit card transactions collected over two days. It contains:

- **Features**: 28 anonymized numerical variables (`V1` to `V28`), plus `Time` and `Amount`.
- **Target**:  
  - `0` = Legitimate transaction  
  - `1` = Fraudulent transaction  
- The dataset is highly imbalanced, with fraud cases making up a very small portion of total transactions.

> **Note:** The dataset file (`creditcard.csv`) is not included in this repository due to size restrictions. You can download it from [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

---

## 🛠️ Tools & Technologies

- Language: Python
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- Environment: Jupyter Notebook

---

## 📈 Model Evaluation

Model performance is measured using:

- Accuracy
---

## 🚀 How to Use

1. Clone or download this repository.
2. Download the dataset from Kaggle and place `creditcard.csv` in the project directory.
3. Open the Jupyter Notebook (`code.ipynb`).
4. Run the notebook to:
   - Load and preprocess data
   - Train the Decision Tree model
   - Evaluate and visualize results

---

## 📌 Possible Improvements

- Apply sampling techniques (e.g., SMOTE, undersampling) to address class imbalance.
- Prune the tree or adjust max depth to avoid overfitting.
- Compare performance with other models like Random Forest, Logistic Regression, or XGBoost.
- Use Grid Search for hyperparameter tuning.

---

## 📄 License

This project is open-source and intended for educational and research purposes.
