# Fraud Detection Model

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Project Status](https://img.shields.io/badge/status-active-brightgreen)](https://github.com/Fidelis-Akinbule/SimpleFraudDetectionModel)

## Overview

This project implements a machine learning solution for detecting fraudulent financial transactions. The system employs supervised learning algorithms to classify transactions as legitimate or fraudulent, utilizing a comprehensive pipeline that includes data exploration, preprocessing, model training, and evaluation.

**Objective:** Develop a binary classifier to accurately predict fraudulent transactions using structured financial data.

---

## Project Structure

```
SimpleFraudDetectionModel/
│
├── data/
│   ├── fraudtrain.csv               # Training data
│   └── fraudtest.csv                # Test data
│
├── SimpleFraudDetectionPrediction.ipynb   # Main notebook
├── README.md                              # Project documentation
└── requirements.txt                       # Project dependencies
```

---

## Dataset Description

The dataset consists of simulated credit card transactions, divided into training and testing sets:

- **fraudtrain.csv** – Labeled training data for model development
- **fraudtest.csv** – Independent test data for model validation

Each dataset includes transaction features such as amount, category, merchant, gender, state, and job, along with a binary target variable `is_fraud` (1 = fraudulent, 0 = legitimate).

---

## Technology Stack

- **Language:** Python 3.8+
- **Core Libraries:**
  - pandas, numpy – Data manipulation and analysis
  - matplotlib, seaborn – Data visualization
  - scikit-learn – Machine learning algorithms and evaluation
  - imbalanced-learn – Class imbalance handling (optional)

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Fidelis-Akinbule/SimpleFraudDetectionModel.git
cd SimpleFraudDetectionModel
```

### 2. Set Up Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

For class imbalance handling:

```bash
pip install imbalanced-learn
```

### 4. Launch the Notebook

```bash
jupyter notebook SimpleFraudDetectionPrediction.ipynb
```

---

## Implementation Features

- Exploratory Data Analysis (EDA)
- Train/Test data separation
- Class imbalance analysis
- Feature preprocessing and encoding
- Multiple model training (Logistic Regression, Decision Tree, Random Forest)
- Comprehensive evaluation using Confusion Matrix, Classification Report, and ROC-AUC
- Model selection and final testing

---

## Evaluation Metrics

The trained models are evaluated using standard classification metrics:

- **Accuracy**
- **Precision and Recall**
- **F1 Score**
- **Confusion Matrix**
- **ROC-AUC Curve**

Detailed performance metrics and visualizations are available in the notebook's final section.

---

## Future Enhancements

- Pipeline-based preprocessing implementation
- Ensemble methods and gradient boosting (XGBoost, LightGBM)
- Model explainability with SHAP
- Web deployment using Flask or Streamlit
- Automated hyperparameter tuning with GridSearchCV

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/licenses/MIT) file for details.

---

## Acknowledgements

- Dataset gotten from kaggle kartik2112/fraud-detection
- Developed to address the critical need for intelligent fraud detection systems
- Part of ongoing data science research and development

---

## Author

**Fidelis Akinbule**

- GitHub: [Fidelis-Akinbule](https://github.com/Fidelis-Akinbule)
- LinkedIn: [fidelis-akinbule](https://www.linkedin.com/in/fidelis-akinbule/)

---

*"Effective fraud detection systems combine predictive analytics with operational excellence to safeguard financial transactions."*
