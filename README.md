# 🚗 Car Price Prediction using Machine Learning

> Turning real-world used car data into intelligent price predictions using Machine Learning.

---

## 📌 Overview

Estimating the right price for a used car is often difficult due to multiple influencing factors such as age, mileage, fuel type, transmission, and ownership history.  
This project builds a **machine learning regression model** to predict the **selling price of used cars** using data from the **CarDekho dataset**.

The project demonstrates a complete **end-to-end ML workflow**, from data preprocessing to model evaluation and visualization.

---

## 🎯 Problem Statement

Used car prices vary significantly, and manual price estimation can be inaccurate.  
The objective of this project is to:

- Analyze historical car data  
- Understand factors affecting car prices  
- Build a regression model to predict selling prices  

---

## 🧠 Approach & Methodology

The project follows these steps:

1. Data loading and inspection  
2. Data preprocessing and cleaning  
3. Encoding categorical features  
4. Feature and target variable separation  
5. Train-test data split  
6. Model training using Linear Regression  
7. Model evaluation using R² score  
8. Visualization of predicted vs actual prices  

---

## 📂 Dataset Information

- **Source**: CarDekho  
- **Total Records**: 4,340  
- **Total Features**: 8  

### Feature Description

| Feature | Description |
|-------|------------|
| name | Car model name |
| year | Manufacturing year |
| selling_price | Selling price (Target Variable) |
| km_driven | Kilometers driven |
| fuel | Fuel type |
| seller_type | Seller category |
| transmission | Manual or Automatic |
| owner | Ownership history |

---

## 🧹 Data Preprocessing

- Checked for missing values (none found)
- Encoded categorical features into numerical values
- Removed irrelevant feature (`name`)
- Split dataset into **90% training** and **10% testing**

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab  

---

## 🤖 Machine Learning Model

- **Algorithm**: Linear Regression  
- **Evaluation Metric**: R² Score  

Linear Regression was chosen as a baseline model for its simplicity and interpretability.

---

## 📊 Model Performance

| Dataset | R² Score |
|-------|---------|
| Training Data | ~0.43 |
| Test Data | ~0.51 |

These scores indicate a **moderate predictive performance**, suitable for a baseline regression model.

---

## 📈 Visualizations

- Scatter plots comparing:
  - Actual vs Predicted Prices (Training Data)
  - Actual vs Predicted Prices (Test Data)

These plots help visualize model accuracy and prediction spread.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-price-prediction-ml.git
2. Open the notebook in Google Colab or Jupyter Notebook
3.Upload the dataset CSV file
4.Run the notebook cells sequentially

## 🔮 Future Enhancements

This project can be improved by:
-Applying feature scaling
-Using One-Hot Encoding
-Trying advanced models:
-Lasso Regression
-Random Forest Regressor
-XGBoost
-Hyperparameter tuning
-Deploying the model using Streamlit

## 👩‍💻 Author
Disha Roy
