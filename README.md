# Credit Card Fraud Detection using Ensemble Methods (AdaBoost and Majority Voting)

## Overview
This project aims to detect credit card fraud using ensemble learning methods, specifically **AdaBoost** and **Majority Voting**. The dataset used contains transaction details, including features such as transaction amount, merchant, and customer information. The goal is to classify transactions as either legitimate or fraudulent.

### Key Features:
- **Ensemble Methods**: Utilizes AdaBoost and Majority Voting to improve model performance.
- **Data Preprocessing**: Handles imbalanced data and applies techniques like SMOTE for oversampling.
- **Evaluation**: Performance metrics such as accuracy, precision, recall, and F1 score are computed.
- **Visualization**: Interactive graphs and plots to better understand the performance and model decision-making process.

---

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib & Seaborn
- imbalanced-learn (for oversampling techniques like SMOTE)

---

## Dataset
The dataset used is a simulated credit card transaction dataset, containing features that represent transaction details. The target variable indicates whether the transaction was fraudulent (1) or legitimate (0).

> **Note:** For the sake of this project, we have used a publicly available dataset, such as the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

---

## Installation

Example Outputs
Model Performance
Here’s an example of what the evaluation output may look like:

Accuracy: 98.5%
Precision: 92.7%
Recall: 91.2%
F1-Score: 91.9%

### Clone the Repository
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection

