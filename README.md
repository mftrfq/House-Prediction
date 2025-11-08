# House Price Prediction

## 📖 Overview  
This notebook builds a regression model to predict **house prices** based on numerical and categorical property features such as area, rooms, and location.  
It covers the full analytical process — from **data preprocessing** and **exploration** to **model training, evaluation, and comparison** — to determine the most accurate prediction approach.

---

## 🧩 Workflow Summary

### 1. Data Preprocessing
- Load and inspect the dataset  
- Handle missing or inconsistent values  
- Convert data types and normalize numerical features  
- Encode categorical features using Label Encoding / One-Hot Encoding  

### 2. Exploratory Data Analysis (EDA)
- Examine data distributions and correlations  
- Visualize relationships between features (e.g., area vs. price, rooms vs. price)  
- Identify outliers and feature importance  

### 3. Modeling
Multiple regression models were trained and compared:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **XGBoost / Gradient Boosting Regressor**

### 4. Model Evaluation
Evaluation metrics:
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

### 5. Insights
- Larger area and number of rooms are key drivers of price.  
- Random Forest performed best in balancing bias and variance.  
- Outlier handling and feature scaling improved model performance.  

---

## 🛠️ Technologies Used  
- **Python 3**  
- **Pandas**, **NumPy** – for data manipulation  
- **Matplotlib**, **Seaborn** – for visualization  
- **Scikit-learn** – for modeling and evaluation  
- **XGBoost**, **LightGBM** – for advanced regression  
- **Jupyter Notebook** – for analysis and documentation  

---
