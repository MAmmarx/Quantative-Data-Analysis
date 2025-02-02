# Quantative-Data-Analysis
This project is about Exploratory data analysis (EDA) &amp; machine learning models to predict diabetes. Includes heatmaps, scatter plots, histograms, and classification models (Logistic Regression, KNN, Naïve Bayes, Decision Tree, Random Forest).


# 🏥 Diabetes Dataset Analysis & Prediction

## 📌 Overview  
This project performs **exploratory data analysis (EDA) and machine learning classification** on a diabetes dataset.  
We visualize feature relationships, handle missing values, and apply various **machine learning models** to predict diabetes outcomes.

---

## 📂 Dataset  
The dataset used is **DiabetesDataset.csv**, which contains medical data on patients, including:  
- Pregnancies  
- Blood Pressure  
- BMI (Body Mass Index)  
- Age  
- Skin Thickness  
- Glucose Levels  
- Insulin  
- Diabetes Pedigree Function  
- Outcome (0 = No Diabetes, 1 = Diabetes)

---

## 🛠️ Features & Methods  

### ✅ **1. Data Preprocessing**  
- Load dataset using **Pandas**  
- Check for missing values and fill them using the **mean**  
- Compute summary statistics: **mean, median, mode, standard deviation, variance**  
- Display dataset correlation using a **heatmap**  

### ✅ **2. Exploratory Data Analysis (EDA)**  
- **Heatmap:** Visualizes correlation between features  
- **Scatter Plot:** Blood Pressure vs BMI relationship  
- **Histogram Plots:** Distributions of pregnancies, age, and skin thickness  
- **Pie Chart:** Distribution of diabetes outcomes  
- **Boxplots:** Identify outliers in features  

### ✅ **3. Machine Learning Models**  
We implement and compare the accuracy of the following classifiers:  
- **Logistic Regression**  
- **K-Nearest Neighbors (KNN)**  
- **Naïve Bayes (GaussianNB)**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  

Each model is trained using **train-test splitting (80-20 & 70-30)** and evaluated using **accuracy scores**.

---

## 📊 Visualizations  

### 🔥 **Heatmap (Feature Correlation)**
![Heatmap](assets/heatmap.png)

### 🎯 **Scatter Plot (Blood Pressure vs BMI)**
![Scatter Plot](assets/scatter.png)

### 📊 **Histogram of Pregnancies**
![Histogram](assets/histogram.png)

---

## 🛠️ Installation & Usage  
### **🔹 Prerequisites**  
Ensure you have **Python 3+** installed along with the following libraries:  
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
