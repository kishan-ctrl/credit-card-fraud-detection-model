# Credit Card Fraud Detection using Machine Learning

## Project Overview
This project explores whether machine learning can accurately detect fraudulent credit card transactions. Credit card fraud is a major financial problem for banks, businesses, and customers, and automated fraud detection systems are essential for reducing financial losses.

The study uses a real-world imbalanced dataset of credit card transactions and applies data science techniques such as preprocessing, exploratory data analysis (EDA), dimensionality reduction, and machine learning models to identify fraudulent transactions.

---

## Research Question
Can machine learning models accurately detect fraudulent credit card transactions from normal transactions?

---

## Dataset
This project uses the **Credit Card Fraud Detection Dataset** from Kaggle.

- **Source:** Kaggle
- **Dataset Name:** Credit Card Fraud Detection Dataset
- **Link:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Facts
- 284,807 total transactions
- 492 fraudulent transactions
- Highly imbalanced dataset

### Features
- `Time` = seconds elapsed between transactions
- `V1` to `V28` = anonymized PCA-transformed features
- `Amount` = transaction amount
- `Class` = target variable  
  - `0` = Normal transaction  
  - `1` = Fraudulent transaction  

---

# Credit Card Fraud Detection

## Methods Used
### 1. Data Preprocessing

Loaded the dataset into Python

Checked for missing values

Examined class imbalance

Prepared features and target variable for model training

### 2. Exploratory Data Analysis (EDA)

Transaction class distribution

Transaction amount distribution

Fraud vs normal transaction comparison

Average transaction amount by class

Principal Component Analysis (PCA)

Scree plot

Number of transactions by class

Class-wise comparison of selected features

Correlation heatmap

Scatter plot analysis

### 3. Machine Learning Models

The following models were used:

Logistic Regression

Random Forest Classifier

Neural Network Model

## Key Findings

The dataset is highly imbalanced, with fraud cases representing only a very small proportion of all transactions.

Transaction amount alone is not enough to identify fraud.

PCA-based features preserve important transaction patterns while protecting sensitive information.

Random Forest performed better than the other evaluated models in identifying fraudulent transactions.

Fraud detection requires evaluation metrics beyond accuracy, especially precision, recall, and F1-score.

## Reflection

This project highlighted the challenges of working with imbalanced datasets and the importance of selecting suitable evaluation metrics for fraud detection. It also demonstrated how machine learning can support financial security by identifying suspicious transaction behavior automatically.

## Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

TensorFlow / Keras

Google Colab

## Installation

Clone this repository and install the required libraries:

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
```

## Usage

Open the notebook in Jupyter Notebook or Google Colab and run all cells step by step.
