# 🌸 Iris Dataset Analysis

Exploratory Data Analysis (EDA) and visualization of the classic **Iris dataset** using Python — focusing on uncovering the unique characteristics of three iris species through **sepal** and **petal** measurements.

---

## 📌 Objective
The goal of this project is to **explore and visualize** the Iris dataset to better understand the differences between **Setosa**, **Versicolor**, and **Virginica** based on their:

- Sepal length
- Sepal width
- Petal length
- Petal width

---

## 📂 Dataset

- **Source:** Loaded from the Seaborn library (`sns.load_dataset("iris")`)
- **Size:** 150 samples
- **Features:**
  - `sepal_length` (cm)
  - `sepal_width` (cm)
  - `petal_length` (cm)
  - `petal_width` (cm)
  - `species` (Setosa, Versicolor, Virginica)

---

## 🛠️ Methods

This project focuses on **data inspection** and **visualization** rather than predictive modeling.

Key steps:
1. **Data loading & structure inspection**
2. **Summary statistics**
3. **Distribution plots**
4. **Scatter plots**
5. **Box plots**
6. **Outlier observation**

---

## 🔍 Key Findings

- **Clean Data:**  
  No missing values; numerical features are `float64` and species is categorical.

- **Species Separation:**  
  - Scatter plots (`sepal_length` vs. `sepal_width`) show **Setosa** clearly separated from the other species.  
  - Petal measurements (`petal_length` & `petal_width`) display strong separation between all species.

- **Distributions:**  
  - `petal_length` & `petal_width` → strongly bimodal by species.  
  - `sepal_width` → roughly normal distribution.  
  - `sepal_length` → slightly bimodal.

- **Size Trends:**  
  - **Setosa** has the smallest petal dimensions.  
  - **Virginica** generally has the largest measurements.

- **Outliers:**  
  Possible outliers in `sepal_width` for Virginica and Setosa.

---

## 📊 Visualizations

The analysis includes:
- **Histograms** for distribution analysis
- **Scatter plots** for feature relationships
- **Box plots** for spotting outliers and size differences

---

## 🚀 Technologies Used
- Python  
- Pandas  
- Seaborn  
- Matplotlib  

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
