# 🏠 House Price Prediction using Random Forest Regression

This project is a Machine Learning based **House Price Prediction System** using the **Random Forest Regressor** algorithm.
It predicts the **Price of a house** based on multiple housing features such as area, bedrooms, bathrooms, quality score, etc.

---

## 📌 Project Highlights
✅ Dataset upload and loading in Google Colab  
✅ Data preprocessing (handle missing values & duplicates)  
✅ Train-Test split (80% train / 20% test)  
✅ Random Forest Regression model training  
✅ Model evaluation using **R² Score**  
✅ User-input based prediction (real-time testing)

---

## 📂 Dataset Information
- File: `house_price_dataset.csv`
- Total columns: 10
- Target column: `Price`

### Input Features (X)
- `Area_sqft`
- `Bedrooms`
- `Bathrooms`
- `Floors`
- `YearBuilt`
- `DistanceToCityCenter_km`
- `Parking`
- `Garden`
- `QualityScore`

### Output Target (y)
- `Price`

---

## 🛠️ Tech Stack
- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn

---

## 🧠 Algorithm Used
### ✅ Random Forest Regression
Random Forest Regression is an ensemble learning technique that uses multiple decision trees and averages their predictions to improve accuracy and reduce overfitting.

Model used:
- `n_estimators = 300`
- `random_state = 42`
- `max_depth = None`

---

## 🔄 Workflow
1. Data Collection  
2. Data Preprocessing  
3. Feature Selection  
4. Model Training  
5. Model Evaluation  
6. Deployment / Prediction  

---
