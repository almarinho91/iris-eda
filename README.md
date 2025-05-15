# 🌸 Iris Dataset – Data Analysis

This notebook demonstrates an **end-to-end exploratory data science project** using the classic **Iris dataset**. It covers everything from dataset inspection to statistical analysis, visual exploration, and supervised machine learning.

> **Author:** André Lopes Marinho  
> **Goal:** Showcase core data science skills through analysis, statistics, visualization, and predictive modeling using Python.

---

## 📚 Learning Objectives

### 🧾 Data Understanding
- Loading structured data with `pandas`
- Inspecting data with `.info()`, `.describe()`, `.value_counts()`

### 📈 Descriptive Statistics
- Mean, median, mode
- Variance, standard deviation
- Distribution interpretation

### 📊 Data Visualization
- Histograms + KDE plots
- Boxplots, Violin plots
- Pairplots (feature relationships)
- Visual pattern recognition for feature usefulness

### 📐 Statistical Inference
- Hypothesis formulation
- Two-sample **t-tests**
- **P-values** and confidence intervals
- Verifying visual differences statistically

### 🧠 Machine Learning
- Data prep and train/test split
- Supervised classification:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Trees
- Evaluation metrics:
  - Accuracy
  - Confusion matrix
  - Precision, recall, F1-score

---

## 📊 Dataset Overview

The **Iris dataset** is a classic in machine learning and statistics. It includes **150 samples** from **three iris species**:
- *Iris setosa*
- *Iris versicolor*
- *Iris virginica*

Each sample includes four numeric features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
  - Species (Setosa, Versicolor, Virginica)

📥 **Source:**  
Dataset from Seaborn: [iris.csv](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv)

---

## 🛠️ Installation & Environment Setup

To run this project locally, follow the steps below.

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/iris-eda.git
cd iris-eda
```

### 2. (Optional) Create a virtual environment
```bash
python -m venv venv
# macOS/Linux
source venv/bin/activate
# Windows
venv\Scripts\activate
```

### 3. Install required packages
```bash
pip install -r requirements.txt
```
