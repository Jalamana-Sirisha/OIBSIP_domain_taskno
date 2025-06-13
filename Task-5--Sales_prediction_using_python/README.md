# 📈 Sales Prediction using Python 

## 📌 Objective

The objective of this project is to build a **predictive model** that estimates future sales based on advertising investments across **TV**, **Radio**, and **Newspaper** channels. By analyzing the relationship between advertising spend and sales, this project helps businesses forecast revenue and optimize marketing strategies using Python and machine learning techniques.

---

## 🛠️ Tools and Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `pandas` – data handling
  - `numpy` – numerical operations
  - `matplotlib` & `seaborn` – data visualization
  - `scikit-learn` – machine learning (Linear Regression, metrics, model evaluation)

---

## 🔍 Steps Performed

### 1. **Data Loading and Cleaning**
- Loaded the `Advertising.csv` dataset using `pandas`.
- Dropped unnecessary columns such as `"Unnamed: 0"`.
- Verified data integrity using `.info()`, `.isnull().sum()`, and `.describe()`.

### 2. **Exploratory Data Analysis (EDA)**
- **Correlation Matrix** and heatmap to identify strong relationships (TV and Sales had the highest correlation).
- **Pairplots and Scatter Plots** with regression lines to visually assess linearity.
- **Distribution Plots** to understand spread and skew of features.
- Used `seaborn.lmplot()` for visualizing regression trends.

### 3. **Data Preprocessing**
- Split the dataset into **features (X)** and **target (y)**.
- Performed an 80/20 **train-test split** for model evaluation.
- Standardized features using `StandardScaler` for better optimization.

### 4. **Model Building: Linear Regression**
- Initialized and trained a **LinearRegression** model.
- Model learned coefficients for TV, Radio, and Newspaper features to predict Sales.

### 5. **Model Evaluation and Prediction**
- Evaluated using:
  - **R² Score**: Measures how well the model explains variance.
  - **Mean Squared Error (MSE)**: Measures average squared prediction error.
  - **Cross-validation R²** (5-fold): Ensures generalizability.
- Made predictions for:
  - Test data
  - New input (e.g., `TV=100`, `Radio=50`, `Newspaper=20`)
- Plotted **Actual vs. Predicted Trends** to visualize performance.

---

## ✅ Outcome

- The Linear Regression model showed a **strong fit**, with a high R² score.
- TV advertising was found to have the **strongest impact on sales**.
- The model can accurately predict sales based on new advertising inputs.
- Visuals confirmed the model's effectiveness, and evaluation metrics validated its reliability.

---

## 📂 Summary

This project successfully demonstrates how **machine learning** can be used to develop a **data-driven sales prediction model**. The combination of data visualization, regression modeling, and performance evaluation provides a solid framework for real-world business forecasting.

---

