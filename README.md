# 🏠 California House Price Predictor

## 📌 Project Overview
A Machine Learning project that predicts California house prices 
using Linear Regression model.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset
California Housing Dataset (built into scikit-learn)
- Total Rows: 20,640
- Total Features: 8

## 📈 Model Performance
| Metric | Score |
|--------|-------|
| MAE    | 0.533 |
| RMSE   | 0.746 |
| R²     | 0.576 |


## 📊 Task 2 - Model Comparison

### Feature Scaling
- Applied StandardScaler to normalize all input features

### Models Trained
| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | 0.7446 | 0.5758 |
| Ridge Regression | 0.7446 | 0.5758 |
| Decision Tree | 0.7242 | 0.5997 |

### ✅ Best Model: Decision Tree Regressor
- R² Score: 0.5997
- RMSE: 0.7242
- Reason: Captures non-linear relationships better than linear models

## 📁 Updated Project Structure
house-price-predictor/
├── task1_ml_linear_regression.ipynb
├── house_price_model.pkl
├── task2_best_model.pkl
└── README.md

## 🚀 How to Run
1. Clone the repository
git clone https://github.com/raj262007/-house-price-predictor.git

2. Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

3. Open Jupyter Notebook
jupyter notebook

4. Open `task1_ml_linear_regression.ipynb`

## 📁 Project Structure
house-price-predictor/
├── task1_ml_linear_regression.ipynb
├── house_price_model.pkl
└── README.md

## 🎯 Results
- Predicted House Price (USD): $452,600
- Predicted House Price (INR): ₹37,792,100
