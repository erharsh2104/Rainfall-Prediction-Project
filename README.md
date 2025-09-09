# 🌧️ Rainfall Prediction Project

This project uses the **Austin Weather dataset** to predict daily **precipitation (rainfall)** using **Linear Regression** in Python.  

---

## 📖 Description
This project focuses on predicting daily **rainfall levels** in Austin, Texas, using historical weather data.  
The dataset includes weather attributes such as **temperature, humidity, dew point, visibility, wind speed, and sea-level pressure**.  

By applying **data cleaning, preprocessing, and linear regression modeling**, the project demonstrates how different weather parameters influence precipitation.  
The goal is not only to **predict rainfall amounts** but also to **visualize and understand trends** through correlation heatmaps, scatter plots, and actual vs predicted comparisons.  

---

## 📌 Project Overview
The objective of this project is to:
- Clean and preprocess the Austin weather dataset  
- Handle missing values and special symbols like `"T"` (trace) and `"-"`  
- Explore weather features such as temperature, humidity, visibility, and wind  
- Build a **Linear Regression model** to predict precipitation  
- Evaluate the model with metrics (RMSE and R² score)  
- Visualize data trends and model results  

---

## 📊 Dataset
- **Source:** Austin Weather dataset (CSV)  
- **Features:**  
  - Temperature (High, Avg, Low)  
  - Humidity (High, Avg, Low)  
  - Dew Point  
  - Visibility (High, Avg, Low)  
  - Wind (High, Avg, Gust)  
  - Sea Level Pressure  
  - Precipitation (target variable)  

---

## ⚙️ Steps Performed
1. **Data Loading & Inspection**  
2. **Data Cleaning & Preprocessing**  
   - Removed irrelevant columns (`Date`, `Events`)  
   - Handled missing values & replaced `"T"` with `0`  
   - Converted all features to numeric  
3. **Feature Selection** – Used all relevant numeric features  
4. **Train-Test Split** – 80% training, 20% testing  
5. **Model Training** – Linear Regression with scikit-learn  
6. **Evaluation** – RMSE and R² metrics  
7. **Visualization** – Correlation heatmap, scatter plots, Actual vs Predicted plot  

---

## 📈 Results
- **Model Evaluation:**  
  - RMSE (Root Mean Squared Error)  
  - R² Score (explained variance of precipitation prediction)  

- **Insights:**  
  - Precipitation increases with humidity  
  - Lower visibility often correlates with rainfall  
  - Predictions align fairly well with actual precipitation values  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** – Data handling  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Machine learning model  

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/erharsh2104/rainfall-prediction.git
   cd rainfall-prediction

jupyter notebook Rainfall_Prediction_Project.ipynb

## ✨ Author
👨‍💻 Harsh Tripathi
Student, Indian Institute of Information Technology, Raichur, Karnataka
📧 tripathiharsh2104@gmail.com

