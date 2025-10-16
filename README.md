# Car Price Prediction using ANN
---------------------------------
## 📖 Overview
This project uses an Artificial Neural Network (ANN) model to predict car prices based on multiple vehicle attributes. The model learns patterns and relationships between features like mileage, engine size, year of manufacture, and fuel type to estimate the market value of cars accurately.

## 🎯 Objective
The main goal is to develop a deep learning model that can effectively predict the resale price of a car, helping customers and dealers make data-driven pricing decisions.

## 🧠 Model Details
- **Model Type:** Artificial Neural Network (ANN)
- **Framework:** TensorFlow / Keras
- **Layers Used:** Input layer, multiple hidden dense layers (with activation functions like ReLU), and a final output layer for regression.
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam

## 🧩 Dataset
The dataset contains information about cars such as:
- Year of manufacture
- Present price
- Kilometers driven
- Fuel type
- Transmission
- Owner count

The target variable is the **Selling Price** of the car.

## Workflow
1. Data preprocessing and feature encoding  
2. Normalization of input features  
3. Splitting data into training and testing sets  
4. Building and compiling the ANN model  
5. Training and evaluating model performance  

## 📊 Evaluation
- Performance is measured using metrics such as **RMSE**, **MAE**, and **R² score**.
- Visualization includes training vs validation loss curves for model evaluation.

## 🚀 Results
The ANN model demonstrates strong predictive accuracy, effectively capturing complex relationships among car attributes, leading to reliable car price estimations.

## 🧾 Conclusion
This deep learning approach provides a scalable and intelligent solution for car price prediction that can be adapted to real-world applications like used car valuation systems and auto marketplaces.
