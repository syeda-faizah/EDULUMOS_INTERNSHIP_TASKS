# House Price Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Libraries](https://img.shields.io/badge/Pandas%2CNumPy%2CMatplotlib%2CSeaborn%2CScikit--learn-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

**Internship:** EduLumos Data Science Internship  
**Task:** Task 2 – Linear Regression using Simple Dataset – House Price Prediction 
**Name:** Syeda Faizah  
**Domain:** Data Science  

---

## Project Overview

This project predicts house sale prices using **Linear Regression**.  
It demonstrates a complete regression workflow including:

- Exploratory Data Analysis (EDA)  
- Data preprocessing  
- Model building and evaluation  
- Feature interpretation  

The dataset includes numerical and categorical features about property size, quality, location, and construction details.

---

## Dataset

The dataset contains:

- **Property size:** LotArea, GrLivArea, TotalBsmtSF, 1stFlrSF, 2ndFlrSF, GarageArea  
- **House quality and condition:** OverallQual, OverallCond  
- **Garage and basement details**  
- **Sale-related attributes**  

**Target variable:** `SalePrice`  

> **Dataset Link:** [House Prices – Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

---

## Exploratory Data Analysis (EDA)

- Histograms of numerical features to understand distributions  
- Scatter plots to analyze relationships between features and `SalePrice`  
- Correlation analysis to identify important features  

**Key findings:**  
`GrLivArea`, `TotalBsmtSF`, `1stFlrSF`, and `GarageArea` are the most correlated with house prices.

---

## Data Preprocessing

- Filled missing numerical values using **mean imputation**  
- Converted categorical variables using **one-hot encoding**  
- Removed irrelevant columns such as `Id`  
- Split data into training and testing sets (80–20 ratio)  

---

## Model Building

- **Linear Regression** model was trained on the training data  
- Predictions were made on the test data  
- Evaluation metrics used: **Mean Squared Error (MSE)**, **R² Score**  

---

## Model Evaluation

- **R² Score:** 0.68 → explains a reasonable portion of variance  
- **MSE:** measures prediction error magnitude  
- Residual plots and Actual vs Predicted plots confirm effective learning

---

## Feature Importance

The most influential features:

- `GrLivArea`  
- `TotalBsmtSF`  
- `1stFlrSF`  
- `GarageArea`  

> Indicates that livable area and structural characteristics strongly impact house prices.

---

## How to Run

1. Clone the repository:  
```bash
git clone https://github.com/syeda-faizah/EDULUMOS_INTERNSHIP_TASKS.git
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open and run the notebook:
```bash
jupyter notebook SyedaFaizah_Week2_HousePricePrediction.ipynb
```

## Folder Contents

- `SyedaFaizah_Week2_HousePricePrediction.ipynb` → Jupyter Notebook with full code  
- `house_price_train.csv` → Dataset used for training  
- `SyedaFaizah_Week2_Report.pdf` → Internship report for Task 2  
- `README.md` → This file

## Conclusion

This project demonstrates a full regression workflow for predicting house prices.
Linear Regression, supported by proper preprocessing and feature selection, provides meaningful insights into house value estimation.
