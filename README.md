# Advertising Sales Prediction with Regression Models

This project demonstrates the use of various regression algorithms to predict advertising sales based on marketing spends across TV, Radio, and Newspaper. It includes data exploration, visualization, preprocessing, and model evaluation with a 3D regression hyperplane visualization.

---

## **Dataset**

The dataset used in this project is `advertising.csv` containing the following features:

- `TV`: Advertising spend on TV
- `Radio`: Advertising spend on Radio
- `Newspaper`: Advertising spend on Newspaper
- `Sales`: Sales generated

---

## **Project Overview**

1. **Data Exploration & Visualization**
   - Histograms with mean, mode, and standard deviation
   - Boxplots to detect outliers
   - Correlation check

2. **Data Preprocessing**
   - Power Transformation using Yeo-Johnson
   - Polynomial Features (degree 2)
   - Standard Scaling

3. **Regression Models**
   - Linear Regression
   - SGD Regressor
   - Ridge Regression
   - Lasso Regression
   - ElasticNet Regression

4. **Evaluation Metrics**
   - R² Score
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)

5. **3D Regression Hyperplane**
   - TV and Radio as axes, with Newspaper fixed at mean value
   - Visualizes the fitted regression plane against actual sales data

6. **Best Model Selection**
   - Automatically selects and saves the best model based on R² score (`best_add_model.pkl`)

---

## **Installation**

```bash
git clone https://github.com/yourusername/Advertising-Sales-Prediction.git
cd Advertising-Sales-Prediction
pip install -r requirements.txt
