# 🏠 California Housing Price Prediction

This project focuses on building a machine learning model to predict housing prices using the California Housing dataset. It demonstrates a complete end-to-end ML workflow including data preprocessing, feature transformation, model training, and evaluation.

---

## 🚀 Key Features

- Performed **data preprocessing** including handling missing values using `SimpleImputer`  
- Applied **feature scaling** using `StandardScaler`  
- Used **ColumnTransformer** for efficient data transformation  
- Implemented and compared multiple models:
  - Linear Support Vector Regression (LinearSVR)
  - Random Forest Regressor  
- Evaluated model performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score  

---

## 📊 Results

### 🌳 Random Forest Regressor
- **R² Score:** 0.82  
- Demonstrates strong performance on non-linear data  

### 📉 LinearSVR
- **R² Score:** -2.66  
- Poor performance due to inability to capture non-linear relationships  

---

## 🧠 Key Insights

- Housing price data contains **non-linear relationships**  
- Ensemble models like Random Forest outperform linear models in such scenarios  
- Proper preprocessing and feature scaling significantly improve model performance  

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib  

---

## 📌 Conclusion

Random Forest Regressor proved to be the most effective model for this problem, achieving strong predictive performance. This project highlights the importance of model selection and understanding data characteristics in machine learning.

---

## ⭐ Project Highlights

- End-to-end ML pipeline implementation  
- Model comparison with clear evaluation metrics  
- Real-world dataset application  
