# 🏡 California Housing Price Prediction

This project predicts the **median house prices** in California districts using features like population, median income, and house characteristics.  
It was built as part of my machine learning practice to learn data preprocessing, model training, and hyperparameter tuning.

---

## 📊 Dataset
The dataset used is the **California Housing dataset**, which contains:
- Longitude, Latitude
- Housing Median Age
- Total Rooms, Total Bedrooms
- Population, Households
- Median Income
- Median House Value (target)

---

## ⚙️ Project Steps
1. Data Exploration and Cleaning  
2. Handling Missing Values (filled with median)  
3. Encoding Categorical Features (e.g., ocean proximity)  
4. Train-Test Split  
5. Model Training (Linear Regression & Random Forest)  
6. Model Evaluation (R² and MSE)  
7. Hyperparameter Tuning using GridSearchCV  
8. Model Export (`.pkl` file)

---

## 🧠 Models and Performance

| Model | R² Score | MSE |
|--------|----------|--------|
| Linear Regression | 0.62 | 4.9e9 |
| Random Forest | **0.81** | 2.3e9 |

After Grid Search tuning:
- **Best R² Score:** 0.8133  
- **Best Parameters:** `{'n_estimators': 200, 'max_depth': None, 'max_features': None}`

---

## 🧰 Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook



 


