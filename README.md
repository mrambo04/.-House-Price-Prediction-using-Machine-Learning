# 🏠 House Price Prediction using Machine Learning

## 📘 Overview
This project builds a predictive model that estimates house prices based on key features such as location, square footage, number of rooms, and other property attributes. The goal is to help buyers and real estate companies make informed decisions through data-driven insights.
 
---
  
## 🎯 Objective
To develop a machine learning model capable of accurately predicting house prices and analyzing the impact of different features on the final price.

---

## 🧰 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn  
- **Techniques:** Data Cleaning, Exploratory Data Analysis (EDA), Feature Engineering, Model Training, Model Evaluation  
- **IDE:** Jupyter Notebook  

---

## 🧮 Approach

### 1. Data Preprocessing
- Loaded and cleaned the dataset (handled missing values, outliers, and categorical encoding).
- Performed normalization and feature scaling where necessary.

### 2. Exploratory Data Analysis (EDA)
- Visualized key relationships using heatmaps, scatter plots, and boxplots.
- Identified top features affecting house prices (e.g., location, number of rooms, area).

### 3. Feature Engineering
- Created new derived features such as price per square foot, total built-up area, etc.
- Used one-hot encoding for categorical variables (like city or property type).

### 4. Model Building
Trained multiple regression models including:
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor  

### 5. Model Evaluation
- Compared models using R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
- Selected the best-performing model (Random Forest) for final predictions.

---

## 📈 Results
| Model | R² Score | MAE | RMSE |
|--------|----------|-----|------|
| Linear Regression | 0.72 | 1.96 | 2.65 |
| Decision Tree | 0.85 | 1.41 | 1.98 |
| **Random Forest (Best)** | **0.87** | **1.25** | **1.74** |

📊 The Random Forest model achieved the highest accuracy with an R² of **0.87** and effectively captured non-linear relationships between house attributes and prices.

---

## 📂 Dataset
- **Source:** [Kaggle]
- **Size:** ~10,000 records  
- **Features:** Location, Area, Bedrooms, Bathrooms, Price, etc.

---

## 📊 Visual Insights
- Prices are highly correlated with location and area.  
- Urban properties show significantly higher price variance.  
- Outlier detection reduced skewness and improved model performance.

---

## 🧑‍💻 Author
**Ram Bevara**  
_Data Analyst & Machine Learning Developer_  
📧(rambabubevara004@gmail.com)  

---

⭐ *If you like this project, don’t forget to star the repo!* ⭐
