# 🏠 House Price Prediction System using Machine Learning

## 📌 Project Overview
The **House Price Prediction System** is a Machine Learning regression-based project developed to predict house prices using the Kaggle dataset (`train.csv`).  

This project helps estimate the selling price of houses based on important features such as:

- Overall Quality  
- Living Area  
- Number of Rooms  
- Neighborhood  
- Garage Size  
- Year Built  

The target column for prediction is:

✅ **SalePrice**

---

## 🎯 Objective
The main objectives of this project are:

- To perform data preprocessing and cleaning  
- To handle missing values effectively  
- To encode categorical variables into numerical form  
- To train a regression model for accurate house price prediction  
- To evaluate the model using performance metrics  

---

## 📂 Dataset Information
Dataset Used: **Kaggle - House Prices Advanced Regression Dataset**

- File: `train.csv`
- Rows: 1460  
- Columns: 81  
- Target Feature: `SalePrice`

---

## 🛠 Technologies & Tools Used
This project is implemented using:

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Pickle (for saving the model)

---

## ⚙️ Project Workflow

### ✅ Step 1: Load Dataset
The dataset is loaded using Pandas.

### ✅ Step 2: Data Cleaning
Missing values are handled by:

- Filling numerical columns with median  
- Filling categorical columns with mode  

### ✅ Step 3: Feature Encoding
Categorical features are converted into numerical format using **One-Hot Encoding**.

### ✅ Step 4: Train-Test Split
The dataset is split into:

- 80% Training Data  
- 20% Testing Data  

### ✅ Step 5: Model Training
A **Random Forest Regressor** model is trained to predict house prices.

### ✅ Step 6: Model Evaluation
Model performance is evaluated using:

- **R² Score**
- **RMSE (Root Mean Square Error)**

### ✅ Step 7: Save Model
The trained model is saved as:

```bash
house_price_model.pkl
.
### Author
Shreyansh Kumar


