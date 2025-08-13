# Iris-Dataset-Analysis
Exploratory data analysis and visualization of the Iris dataset using Python, focusing on understanding the characteristics of different iris species based on their sepal and petal measurements

**Task Objective:**
The objective of this project is to explore and visualize the Iris dataset to understand the characteristics of different iris species based on their sepal and petal measurements.

**Dataset Used:**
The dataset used is the classic Iris dataset, loaded from the seaborn library. It contains 150 samples of iris flowers with measurements of sepal length, sepal width, petal length, petal width, and the species of iris (setosa, versicolor, or virginica).

**Models Applied:**
No specific machine learning models were applied in this notebook. The analysis focuses on data loading, inspection, and visualization techniques to explore the dataset.

**Data Analysis Key Findings:**
The dataset contains 150 entries and 5 columns: sepal_length, sepal_width, petal_length, petal_width, and species.
There are no missing values in the dataset.
The numerical columns (sepal_length, sepal_width, petal_length, petal_width) have appropriate float64 data types, and the species column has an object data type.
The scatter plot of sepal length versus sepal width shows distinct groupings by species, with Setosa clearly separated from Versicolor and Virginica.
Histograms reveal that petal_length and petal_width have strongly bimodal distributions, indicating clear separation based on species, while sepal_width is roughly normally distributed and sepal_length appears somewhat bimodal.
Box plots show that Setosa has significantly smaller petal length and petal width compared to Versicolor and Virginica. Virginica generally exhibits the largest measurements across most features.
Potential outliers were observed in the sepal_width for the Virginica and Setosa species according to the box plots.
