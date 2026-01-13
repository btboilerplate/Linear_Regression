# 📈 Linear Regression on Housing Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Linear%20Regression-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 🔹 Project Overview
This project implements Linear Regression using scikit-learn to predict house prices from a housing dataset.
The notebook demonstrates the complete machine learning workflow, including data loading, preprocessing,
model training, prediction, evaluation, and residual analysis.

---

## 📂 Repository Contents
Linear_Regression/
│
├── Linear_Regression.ipynb
├── housing.csv
└── README.md

---

## 📊 Dataset
- File: housing.csv
- Type: Tabular housing data
- Purpose: Used to train and evaluate a linear regression model for house price prediction

---

## 🛠️ Libraries & Tools Used
- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## ⚙️ Project Workflow
1. Load the housing dataset
2. Perform train-test split
3. Train a Linear Regression model
4. Predict house prices on test data
5. Evaluate model performance using R² Score
6. Visualize residual distribution

---

## 📈 Model Evaluation

R² Score: 0.6395768324695243

Interpretation:
The model explains approximately 64% of the variance in housing prices, which is a reasonable result
for a baseline linear regression model on real-world data.

---

## 📉 Residual Analysis

Residual Distribution:
residuals = y_test - reg_pred
plt.figure()
plt.hist(residuals, bins=30)
plt.xlabel("Residuals")
plt.ylabel("Frequency")
plt.title("Residual Distribution")
plt.show()
<img width="604" height="453" alt="image" src="https://github.com/user-attachments/assets/aa577494-9d42-459c-892a-c8d421ec3a9f" />

Key Insights:
- Residuals are approximately normally distributed
- Indicates that linear regression assumptions are largely satisfied
- Some skewness suggests potential improvement with advanced models

---

## 📌 Key Observations
- Linear Regression provides a strong baseline model
- Model performance can be improved using:
  - Feature engineering
  - Polynomial regression
  - Regularization techniques (Ridge, Lasso)
  - Tree-based or ensemble models

---

## ▶️ How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/Linear_Regression.git

2. Install required libraries
pip install numpy pandas matplotlib scikit-learn

3. Open Linear_Regression.ipynb and run all cells sequentially

---

## 🚀 Future Enhancements
- Add RMSE and MAE evaluation metrics
- Experiment with Polynomial Regression
- Apply feature scaling comparisons
- Try regularized regression models

---
