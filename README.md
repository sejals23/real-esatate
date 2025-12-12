# 🏡 Real Estate Price Prediction & Investment Classification

A complete Machine Learning project that predicts property prices and classifies whether a property is a **good investment** based on city-wise median pricing. This project includes end-to-end data cleaning, feature engineering, visualization, regression models, classification models, and performance evaluation.

---

## 📌 Project Overview
This project aims to:
- Predict **property prices** using supervised ML regression algorithms  
- Identify **good investment properties** (1 = good, 0 = not good)  
- Apply complete EDA and visualization  
- Build ML pipelines for regression & classification  
- Evaluate models with industry-standard metrics  

Dataset includes features such as City, BHK, Area (sqft), Bathroom count, Furnishing, Property Type, and Price in Lakhs.

---

## 🔍 Key Features
- Complete preprocessing & cleaning  
- One-hot encoding of categorical variables  
- Feature engineering: **Good_Investment Label**  
- Regression Models:
  - Linear Regression  
  - Random Forest Regressor  
- Classification Models:
  - Logistic Regression  
  - Random Forest Classifier  
- Metrics:
  - RMSE, R²  
  - Accuracy, Precision, Recall, F1-score  
  - Confusion Matrix  
- Rich data visualization with Matplotlib & Seaborn  

---

## 🧼 Data Preprocessing
- Handled missing values  
- Removed duplicates  
- Encoded all categorical features  
- Scaled numerical variables  
- Created new target:
  - **Good_Investment = 1 if price < city median, else 0**

---

## 📊 Exploratory Data Analysis
EDA includes:
- City-wise price comparison  
- BHK vs Price  
- Bathroom count vs Price  
- Property type trends  
- Correlation heatmap  
- Price distribution plots  

---
## 🤖 Machine Learning Workflow

### 🔹 Regression (Price Prediction)
Models:
- Linear Regression  
- RandomForestRegressor  

Metrics:
- MAE  
- MSE  
- RMSE  
- R² Score  

---

### 🔹 Classification (Good Investment Detection)
Models:
- Logistic Regression  
- RandomForestClassifier  

Metrics:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---
## 📈 Results Summary
- Random Forest shows best performance for both regression & classification  
- City-wise median pricing strongly improves classification accuracy  
- The model helps identify undervalued properties effectively  
