# Ridge Regression – EV Car Price Prediction

## 📌 Project Overview

This project uses **Ridge Regression** to predict the price of Electric Vehicles (EVs) in India based on their specifications.

The project uses machine learning techniques such as:

* Data preprocessing
* Feature scaling
* One-hot encoding
* Train-test splitting
* Ridge Regression
* Model evaluation using MAE, RMSE, and R² score

## 📂 Dataset

The project uses the dataset:

`ev_car_India_dataset.csv`

The features used for prediction are:

### Numerical Features

* **Range**
* **Power**
* **Battery**

### Categorical Features

* **Brand**
* **Model**

### Target Variable

* **Price**

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## 🔄 Project Workflow

1. Import the required Python libraries.
2. Load the EV dataset.
3. Explore the dataset and check for missing values.
4. Separate the features (`X`) and target variable (`y`).
5. Identify numerical and categorical features.
6. Apply:

   * `StandardScaler` to numerical features
   * `OneHotEncoder` to categorical features
7. Split the dataset into training and testing sets.
8. Train a Ridge Regression model using different alpha values:

   * 0.01
   * 0.1
   * 1
   * 10
   * 100
9. Generate predictions.
10. Evaluate the model using:

* MAE
* RMSE
* R² Score

## 📊 Model Evaluation

The model is evaluated on both the training and testing datasets.

### Evaluation Metrics

**MAE (Mean Absolute Error)**
Measures the average absolute difference between actual and predicted prices.

**RMSE (Root Mean Squared Error)**
Measures the prediction error while giving more weight to larger errors.

**R² Score**
Shows how well the model explains the variation in EV prices.

## 🚀 How to Run in Google Colab

1. Open the notebook in Google Colab.
2. Upload `ev_car_India_dataset.csv` to the Colab environment.
3. Run the notebook cells in order.
4. Check the final Ridge Regression results and evaluation metrics.

## 🎯 Objective

The main objective of this project is to demonstrate how **Ridge Regression can be used to predict EV prices based on vehicle specifications and categorical information**.

## 👩‍💻 Project Type

**Machine Learning – Regression**

**Algorithm:** Ridge Regression

**Dataset:** Indian Electric Vehicle Dataset
