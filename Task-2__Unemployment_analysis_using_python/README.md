# 📊 Unemployment Analysis in India

## 📌 Objective

The goal of this project is to analyze unemployment trends across various states and regions in India, with a special focus on the **impact of the COVID-19 lockdown**. The analysis aims to uncover regional patterns in employment and unemployment, and to measure how lockdowns affected unemployment rates.

---

## 🛠️ Tools and Technologies Used

- **Python Libraries**:
  - `pandas` – for data loading and manipulation
  - `matplotlib` & `seaborn` – for data visualization
  - `plotly.express` – for interactive visualizations

---

## 🔍 Steps Performed

### 1. **Data Loading and Exploration**
- Loaded the dataset (`Unemployment in India.csv`) into a pandas DataFrame.
- Inspected dataset structure using `.info()`, `.shape`, and `.describe()`.
- Computed and visualized the correlation matrix using `seaborn.heatmap()`.

### 2. **Exploratory Data Analysis (EDA)**
- Renamed columns for clarity (e.g., "Estimated Unemployment Rate", "Region").
- Visualized:
  - The distribution of estimated employed individuals by region using histograms.
  - Unemployment rate across states and regions using a **sunburst chart**.

### 3. **Impact of Lockdown Analysis**
- Converted `Date` to datetime and extracted `Month`.
- Defined periods as **Before Lockdown** (Jan–Apr) and **During/After Lockdown** (Apr–Jul).
- Calculated average unemployment rate per state for both periods.
- Computed **percentage change** in unemployment rates.
- Visualized the change using a **bar chart** to identify the most affected states.

---

## ✅ Outcome

- The analysis revealed **significant regional differences** in employment and unemployment.
- The **sunburst chart** provided an interactive view of unemployment rates by region and state.
- The **percentage change analysis** clearly showed which states were most impacted by the lockdown.
- The project offers valuable insights into how socio-economic events like the pandemic affect labor markets across regions.

---

## 📂 Summary

This project demonstrates how Python-based data analysis can be applied to real-world problems such as unemployment. It emphasizes the role of EDA and visualization in identifying key patterns and supporting data-driven decision-making.

---

