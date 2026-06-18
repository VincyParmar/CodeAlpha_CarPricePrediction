# Car Price Prediction with Machine Learning

## Project Overview

This project was completed as part of the CodeAlpha Data Science Internship.

The main goal of this project is to predict the selling price of a car using machine learning. Different factors such as present price, fuel type, transmission type, owner details, and car age were used to build a model that can estimate car prices.

---

## Objectives

* Understand and explore the car price dataset.
* Clean and prepare the data.
* Create useful features for the machine learning model.
* Train a model to predict car prices.
* Check the model's performance.
* Find out which factors affect car prices the most.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Dataset Features

The dataset includes the following information:

* Car Name
* Year
* Selling Price
* Present Price
* Kilometers Driven
* Fuel Type
* Selling Type
* Transmission
* Owner

**Target Variable:**

* Selling_Price

---

## Data Preprocessing

The following steps were performed before training the model:

* Removed duplicate data.
* Created a new feature called "Car_Age".
* Removed unnecessary columns.
* Converted text data into numerical format using one-hot encoding.
* Prepared the data for model training.

---

## Exploratory Data Analysis

Different graphs were created to understand the data better:

* Selling Price Distribution
* Correlation Heatmap
* Actual vs Predicted Prices
* Feature Importance Analysis

---

## Machine Learning Model

**Model Used:**

* Linear Regression

The dataset was split into:

* 80% Training Data
* 20% Testing Data

---

## Model Performance

**R² Score: 0.75**

The model can explain about **75% of the changes in car selling prices**, which shows good prediction performance.

---

## Key Findings

* Present Price has the biggest impact on Selling Price.
* Older cars usually have lower resale value.
* Diesel cars generally have higher selling prices.
* Manual transmission cars are often sold at lower prices than automatic cars.
* Cars sold by individual owners are usually cheaper than those sold by dealers.

---

## Real-World Applications

* Online car buying and selling websites
* Car price prediction systems
* Car dealership pricing decisions
* Insurance valuation systems
* Used car recommendation platforms

---

## Author

Vincy Parmar
