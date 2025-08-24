# Project Name: Telecom Customer Churn Prediction

## 📋 Description
This project predicts customer churn for a telecom company using machine learning techniques. It includes data preprocessing, model building, and evaluation.

## 📂 Folder Structure
```
Telecom-Customer-Churn-Prediction/
├── Final_model.ipynb         # Jupyter notebook with the trained model
├── pipeline.py               # Python script for the ML pipeline
├── README.md                 # Project documentation
├── data/                     # Folder containing datasets
│   ├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── results/                  # Folder containing model results
```

## 📊 Datasets
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **File**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

## ⚙️ Features
- Data preprocessing (handling missing values, encoding categorical data).
- Exploratory Data Analysis (EDA).
- Model building using algorithms like Logistic Regression, Random Forest, and XGBoost.
- Hyperparameter tuning using Optuna.
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ML-Portfolio.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Telecom-Customer-Churn-Prediction
   ```
3. Run the pipeline script:
   ```bash
   python pipeline.py
   ```

## 📈 Results
- Best model: **Random Forest**
- Accuracy: **91%**
- F1-Score: **0.89**

## 🛠️ Requirements
- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - optuna

## 📄 License
This project is licensed under the MIT License.

## 🙌 Acknowledgements
- Dataset by [Kaggle](https://www.kaggle.com/).
- Tutorials and resources from FreeCodeCamp and Scikit-learn documentation.

---
