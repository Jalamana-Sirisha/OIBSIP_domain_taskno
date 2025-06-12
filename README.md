# OIBSIP_domain_taskno
# 🌸 Iris Flower Classification using KNN

## 📌 Objective
The goal of this project is to classify iris flowers into one of three species—**Iris-setosa**, **Iris-versicolor**, or **Iris-virginica**—based on the measurements of their petals and sepals. The classification is achieved using the **K-Nearest Neighbors (KNN)** algorithm.

---

## 🧪 Tools and Technologies Used
- **Programming Language**: Python  
- **Libraries**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

---

## 🔍 Steps Performed

1. **Data Loading**  
   - Loaded the dataset from a CSV file using `pandas`.

2. **Data Cleaning & Preprocessing**  
   - Dropped the unnecessary 'Id' column.
   - Checked for null values.
   - Converted categorical labels into numerical form using `LabelEncoder`.
   - Scaled features using `StandardScaler`.

3. **Exploratory Data Analysis (EDA)**  
   - Visualized the distribution of features using histograms and scatter plots.
   - Created a heatmap to study correlations among features.

4. **Model Building**  
   - Split the dataset into training and testing sets (60% - 40%).
   - Built a **K-Nearest Neighbors (KNN)** classification model.
   - Trained the model on the training set and evaluated it on the test set.

5. **Model Evaluation**  
   - Calculated the **accuracy score**.
   - Plotted the **confusion matrix**.
   - Performed a **sample prediction** using a new input.

---

## ✅ Outcome

- **Model Accuracy**: 100% on test data
- The confusion matrix confirmed that all test samples were correctly classified.
- A test prediction for input `[5, 2.9, 1, 0.2]` returned **Iris-setosa** as the predicted species.

---

## 📂 Summary
This project demonstrates the effective use of basic machine learning techniques to classify flower species using numerical features. The results show that KNN is a suitable model for this dataset with high accuracy.

---
