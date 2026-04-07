# House-Price-Prediction
# 🏠 House Price Prediction (Machine Learning Project)

## 🧠 Project Overview

This project aims to predict house prices based on various features such as area, location, number of rooms (BHK), and bathrooms.
It uses **machine learning regression models** to estimate property prices accurately.

---

## 🎯 Objective

* Analyze housing dataset
* Perform data preprocessing
* Select important features
* Train regression models
* Predict house prices

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**

---

## 📊 Dataset

* Dataset: Bengaluru House Price Data
* Features:

  * Area (total_sqft)
  * Location
  * Number of rooms (BHK)
  * Bathrooms
* Target:

  * Price 💰

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Handle missing values
* Convert categorical data (location)
* Convert text values (BHK, sqft) into numeric

### 2️⃣ Feature Engineering

* Extract BHK from size column
* Convert area into numeric format

### 3️⃣ Feature Selection

* Select relevant features for prediction
* Remove unnecessary columns

### 4️⃣ Model Training

* Linear Regression
* Decision Tree Regressor

### 5️⃣ Prediction

* Predict house prices using trained models

### 6️⃣ Evaluation

* Mean Squared Error (MSE) used for performance

---

## 🤖 Machine Learning Models

### 🔹 Linear Regression

* Simple and interpretable
* Works well for linear relationships

### 🌳 Decision Tree Regressor

* Captures non-linear relationships
* Better for complex datasets

---

## 📈 Output

* Price distribution graph
* Actual vs Predicted price graph
* Model performance (MSE)

---

## 📌 Results

* Models successfully predicted house prices
* Decision Tree performed better on non-linear patterns
* Visualization helped understand data trends

---

## 💡 Key Concepts

* Data Preprocessing
* Feature Selection
* Regression Models
* Data Visualization

---

## 🚀 Future Improvements

* Use Random Forest (better accuracy)
* Hyperparameter tuning
* Add more features (location encoding improvements)
* Build web app using Flask

---

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib scikit-learn
```

```bash
python main.py
```

---

## 📷 Sample Output

* Graphs showing trends and predictions



---

