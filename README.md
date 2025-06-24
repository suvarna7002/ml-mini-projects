# 🧠 ML Mini Projects

This repository contains small machine learning projects that I built to learn core ML concepts

---

## 📌 Project 1: Linear Regression from Scratch (using NumPy)

### 🔍 Description
This project demonstrates a simple linear regression model built **without using any ML libraries**. It uses:

- Python + NumPy
- Batch Gradient Descent
- Custom Cost and Gradient Functions

### 📊 Dataset
A salary dataset with the columns:
- `YearsExperience`
- `Salary`

> 💾 [Download the dataset](https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression)

### ⚙️ Features
- Load and visualize data using Matplotlib
- Implement cost function and gradient descent manually
- Train the model to find optimal weights
- Predict salaries and visualize the regression line

### ✅ Result
The model successfully learns a linear relationship between years of experience and salary, and performs well on this dataset. 

---

## 📌 Project 2: California Housing Price Prediction using SGDRegressor (Sklearn)

### 🔍 Description
This project uses Stochastic Gradient Descent Regression from sklearn to predict California housing prices based on multiple features. The data is normalized using StandardScaler, and a linear model is trained to capture general pricing trends.


### 📊 Dataset
California Housing dataset from sklearn.datasets.fetch_california_housing, containing features such as:

- Median Income (MedInc)

- House Age (HouseAge)

- Average Rooms (AveRooms)

- Average Bedrooms (AveBedrms)

- Population

- Average Occupancy (AveOccup)

- Latitude

- Longitude

### ⚙️ Features
- Data normalization using StandardScaler
- Linear regression with SGDRegressor
- Comparison of predicted vs actual housing prices

### ✅ Result
The linear SGD model captures general trends but is limited by the linearity assumption, leading to noticable prediction errors on complex housing price data (See Conclusion for more insight).

---

📌 Project: Titanic Survival Prediction using Logistic Regression (Sklearn)
🔍 Description
This project applies logistic regression to predict Titanic passenger survival based on key features. 

📊 Dataset
Titanic passenger data from Kaggle’s Titanic competition, including features such as:

Passenger Class (Pclass)

Sex

Age

Number of Siblings/Spouses aboard (SibSp)

Number of Parents/Children aboard (Parch)

Fare ($)

⚙️ Features

Data cleaning with median imputation for missing Age and Fare

Encoding Sex as binary numeric

Data normalization using StandardScaler

Logistic regression model training and validation with train/test split

Feature importance analysis using model coefficients

Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix visualization
