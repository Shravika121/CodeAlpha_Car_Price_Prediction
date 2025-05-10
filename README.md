**🚗 Car Price Prediction with Machine Learning**

🔍 Overview

This project is part of my CodeAlpha Data Science Internship and focuses on predicting car prices based on various features using supervised machine learning techniques. The aim is to build a regression model that can accurately estimate the price of a car based on attributes like engine size, horsepower, mileage, and brand.

📁 Dataset
Source: Car Price Dataset

Features:

Car brand (extracted from CarName)

Fuel type, engine type, horsepower, city MPG, highway MPG, etc.

Target Variable:

price — the actual market price of the car

📌 Objectives
Clean and preprocess the car dataset

Extract car brand and handle categorical variables

Visualize feature relationships with price

Train a regression model to predict prices

Evaluate model performance using R² score and MSE

🧰 Technologies Used
Python 🐍

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

🛠️ Steps Performed
Data Cleaning:

Removed irrelevant columns like car_ID

Extracted car brand from CarName

Fixed inconsistent brand names (e.g., vw, vokswagen → volkswagen)

Handled categorical features using one-hot encoding

Data Visualization:

Bar plots for average price by brand

Heatmap to show feature correlations

Model Training:

Used Linear Regression from Scikit-learn

Split data into training and testing sets (80/20)

Trained and evaluated the model

📊 Model Performance
R² Score: ~0.85–0.92

Mean Squared Error (MSE): Varies depending on features used

📈 Visualizations
Correlation heatmap

Actual vs. Predicted price scatter plot

Feature importance (optional)

🧪 How to Run
Clone the repository:

git clone https://github.com/your-username/CodeAlpha_Car_Price_Prediction.git
cd CodeAlpha_Car_Price_Prediction
Open the notebook:

jupyter notebook Car_Price_Prediction.ipynb
📢 Internship Acknowledgement
This project was completed as part of the Data Science Internship at CodeAlpha.
