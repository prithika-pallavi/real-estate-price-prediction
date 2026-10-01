# 🏠 Real Estate Price Prediction Using Linear Regression

A machine learning project for predicting house prices using property-related features.

## 📌 Project Overview

The goal of this project is to predict the **house price of unit area** using features such as:

- Transaction date
- House age
- Distance to the nearest MRT station
- Number of convenience stores
- Latitude
- Longitude

The project compares different Linear Regression approaches and evaluates their performance on unseen test data.

## 📊 Dataset

The dataset contains **414 observations** and **6 predictive features**.

### Features

| Feature | Description |
|---|---|
| Transaction Date | Date of the property transaction |
| House Age | Age of the house |
| Distance to MRT | Distance to the nearest MRT station |
| Convenience Stores | Number of nearby convenience stores |
| Latitude | Geographic latitude |
| Longitude | Geographic longitude |

### Target

**House Price of Unit Area**

## 🔬 Methodology

The project follows this workflow:

1. Load the dataset
2. Inspect the data
3. Check missing values
4. Check duplicate records
5. Perform exploratory data analysis
6. Analyze feature correlations
7. Detect potential outliers
8. Split the data into training and testing sets
9. Standardize the features
10. Train Linear Regression models
11. Implement Gradient Descent from scratch
12. Compare model performance

## 🤖 Models

### 1. Simple Linear Regression

Uses the distance to the nearest MRT station as the predictor.

### 2. Multiple Linear Regression

Uses all available property features.

### 3. Multiple Linear Regression with Gradient Descent

Implements the optimization algorithm manually rather than relying entirely on a built-in regression solver.

## 📏 Evaluation Metrics

The models are evaluated using:

- **MAE** — Mean Absolute Error
- **MSE** — Mean Squared Error
- **RMSE** — Root Mean Squared Error
- **R²** — Coefficient of Determination

## 📈 Visualizations

The notebook includes:

- Target distribution
- Feature distributions
- Correlation heatmap
- Feature vs. target plots
- Actual vs. predicted values
- Residual analysis
- Gradient Descent convergence
- Model comparison

## 🛠️ Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 How to Run

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
real_estate_price_prediction.ipynb
```

Make sure the dataset file is in the same directory as the notebook.

## 📂 Project Structure

```text
real-estate-price-prediction/
│
├── real_estate_price_prediction.ipynb
├── Real estate valuation data set.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## 📌 Key Takeaway

This project demonstrates the complete workflow of a supervised machine learning regression problem, from data exploration and preprocessing to model training, evaluation, and comparison.
