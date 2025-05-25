# Revolut LTV Prediction

This project is a machine learning pipeline for predicting the **Customer Lifetime Value (LTV)** of digital wallet users. The dataset used originates from a fintech context, and this notebook walks through the steps from EDA to model evaluation.

## 📂 Project Structure

- `revolut_ltv_prediction.ipynb` — Jupyter notebook containing the complete workflow.
- Dataset source: `digital_wallet_ltv_dataset.csv` (used from Kaggle or Colab runtime).

## 🧠 Objectives

- Load and clean a dataset related to fintech customer data.
- Perform exploratory data analysis (EDA).
- Handle missing values and outliers.
- Encode categorical features and scale numerical data.
- Build predictive models to estimate Customer LTV.
- Evaluate model performance using metrics such as MAE and RMSE.

## 🛠️ Technologies & Libraries

- Python
- pandas, NumPy
- seaborn, matplotlib
- scikit-learn
- XGBoost (likely used in model training)
- Jupyter Notebook (for development and visualization)

## 📊 Workflow Overview

1. **Data Loading**:
   - The dataset is read either from a Kaggle or Colab path.

2. **Data Exploration**:
   - Shape and summary statistics of the dataset.
   - Missing values and duplicate checks.
   - Distribution of categorical features.
   - Visualization of numerical features for outlier detection.

3. **Preprocessing**:
   - Handling of null values and duplicates.
   - One-hot encoding or label encoding for categorical variables.
   - Feature scaling using MinMax or Standard Scaler.

4. **Modeling**:
   - Multiple regression models may be used (e.g., Linear Regression, Random Forest, XGBoost).
   - Train-test split.
   - Model fitting and prediction.

5. **Evaluation**:
   - MAE, MSE, RMSE, and R² score computed.
   - Visual comparison of predicted vs actual LTV values.

## 📈 Potential Outcomes

- Understanding the most important features driving LTV.
- Providing a predictive pipeline that can help fintech firms forecast high-value users.

## 🚀 Getting Started

To run this notebook:
1. Clone the repository.
2. Ensure the dataset (`digital_wallet_ltv_dataset.csv`) is available in your working directory.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```
4. Open the notebook with Jupyter and run all cells.
