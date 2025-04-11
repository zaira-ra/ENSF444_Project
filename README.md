# ENSF444_Project
# Superstore Sales Prediction

This project aims to predict profit from historical sales data provided by a fictional superstore. We use regression models to forecast profit and identify key business drivers.

## 📁 Dataset

- File: `Superstore.csv`
- Columns: Order date, sales, discount, quantity, city, category, sub-category, and more.
- Target variable: `Profit`

## 📊 Objective

Our made-up client is a regional manager of a retail chain who wants to optimize profit predictions based on past order information. We compare multiple machine learning models to identify the best performing one.

## 🧠 Machine Learning Models Used

- Linear Regression (Baseline)
- Random Forest Regressor (Non-linear)
- Gradient Boosting Regressor (Non-linear)

## 🚀 How to Run the Project

### ✅ In Google Colab

1. Open the Colab notebook.
2. Upload the file `Superstore.csv` via the file sidebar (left pane > Files > Upload).
3. Run all cells sequentially (Runtime > Run all).
4. Make sure to allow permissions for runtime restarts if prompted.

### ✅ In Jupyter Notebook (Locally)

1. Clone or download this repo to your local machine.
2. Place `Superstore.csv` in the same directory as the notebook.
3. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
