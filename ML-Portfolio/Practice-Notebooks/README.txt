# Telecom Customer Churn Prediction

## 📋 Description
This project explores various machine learning techniques and approaches to predict customer churn for a telecom company. The same dataset, **WA_Fn-UseC_-Telco-Customer-Churn.csv**, is used across multiple scripts to practice and implement clustering, classification, model optimization, and pipeline creation.

## 📂 Folder Structure
```
Telecom-Customer-Churn-Prediction/
├── README.md                  # Project documentation
├── kmeansclustering.py        # K-Means clustering implementation
├── modeling_after_optuna.py   # Modeling after Optuna optimization
├── optuna_to_find_the_best_model.py # Script for finding the best ML model using Optuna
├── practice_pipeline.py       # Practice script for creating a pipeline
├── svm.py                     # SVM classification implementation
```

## 📊 Dataset
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **File Name**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Description**: The dataset contains customer information such as demographic data, account details, and services used. The target variable is `Churn`, indicating whether a customer has churned (yes/no).

## 🛠️ Scripts Overview
### 1. **kmeansclustering.py**
   - Implements **K-Means Clustering** to group customers based on similar characteristics.
   - Useful for unsupervised learning and understanding customer segments.

### 2. **modeling_after_optuna.py**
   - Applies machine learning models post Optuna optimization.
   - Includes fine-tuned models for better performance.

### 3. **optuna_to_find_the_best_model.py**
   - Uses Optuna to identify the best algorithm for predicting churn.
   - Compares models like **Logistic Regression**, **Random Forest**, and **XGBoost**.
   - Includes preprocessing steps such as handling missing values and encoding categorical features.

### 4. **practice_pipeline.py**
   - Demonstrates how to create a **Pipeline** for preprocessing and modeling.
   - Includes steps like scaling, encoding, and model training.

### 5. **svm.py**
   - Implements **Support Vector Machine (SVM)** for classification tasks.
   - Focuses on separating churn vs. non-churn customers with a decision boundary.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Telecom-Customer-Churn-Prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Telecom-Customer-Churn-Prediction
   ```
3. Run any script using Python:
   ```bash
   python script_name.py
   ```
   Replace `script_name.py` with the desired script (e.g., `kmeansclustering.py`).

## 🛠️ Requirements
- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - optuna

Install the required libraries:
```bash
pip install pandas numpy scikit-learn xgboost optuna
```

## 📈 Results
- **Optuna Optimization**: Identifies the best model LOGISTIC REGRESSION for predicting churn which was used in the project.
- **Clustering**: Groups customers into clusters for better understanding of customer behavior.
- **Pipeline**: Simplifies preprocessing and modeling workflows.

## 📄 License
This project is licensed under the MIT License.

## 🙌 Acknowledgements
- Dataset by [Kaggle](https://www.kaggle.com/).
- Tutorials and resources from FreeCodeCamp, Scikit-learn, and Optuna documentation.

---
