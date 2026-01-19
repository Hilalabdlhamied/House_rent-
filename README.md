# 🏠 House Rent Prediction

## 📌 Project Overview

This project aims to build a **Machine Learning model** that predicts **house rent prices** based on property features, location, and other relevant factors. Accurate rent prediction helps tenants, landlords, and real estate platforms make informed decisions.

The project covers the full data science pipeline: data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

## 🎯 Objective

* Predict monthly house rent accurately
* Analyze the most influential features affecting rent prices
* Compare different regression models
* Improve prediction performance through preprocessing and tuning

---

## 🗂️ Dataset Description

The dataset contains information about rental properties. Each row represents one house or apartment.

### 🔑 Features

* `BHK`: Number of bedrooms, halls, and kitchens
* `Size`: Size of the house (in square feet)
* `Floor`: Floor number of the house
* `Total_Floors`: Total number of floors in the building
* `Area_Type`: Type of area (Super Area, Built Area, Carpet Area)
* `Area_Locality`: Locality of the house
* `City`: City where the house is located
* `Furnishing_Status`: Furnished / Semi-Furnished / Unfurnished
* `Tenant_Preferred`: Preferred tenant type
* `Bathroom`: Number of bathrooms
* `Point_of_Contact`: Contact type for the property

### 🎯 Target Variable

* `Rent`: Monthly rent price

---

## 🧹 Data Preprocessing

* Handling missing values
* Encoding categorical features
* Feature scaling for numerical variables
* Outlier detection and treatment

---

## 📊 Exploratory Data Analysis (EDA)

* Rent distribution analysis
* Relationship between rent and house size
* Impact of city and locality on rent prices
* Correlation analysis between numerical features

---

## 🤖 Machine Learning Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting / XGBoost (optional)

---

## 📈 Model Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 🏆 Results

* Tree-based models outperformed linear regression
* Random Forest achieved the best overall performance
* City, house size, and furnishing status were among the most influential features

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/house-rent-prediction.git

# Navigate to the project directory
cd house-rent-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

---

## 📌 Future Improvements

* Hyperparameter tuning
* Feature importance analysis
* Model deployment using Flask or FastAPI
* Integration with a web-based rent prediction app

---

## 👨‍💻 Author

**Helal Abdelhamid**
Data Scientist | Machine Learning Engineer

---


