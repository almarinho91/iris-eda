# Iris Dataset – Data Science and analysis

This project is a complete walkthrough of the **data science workflow** using the classic Iris flower dataset. It includes data inspection, statistics, visualizations, hypothesis testing, and classification with machine learning models — all presented in a clean, well-documented notebook.

> **Author:** André Lopes Marinho  
> **Goal:** Build and explain a data science pipeline from data exploration to predictive modeling using Python.

---

## What's Inside the Notebook

The notebook `iris_eda.ipynb` includes:

### Analysis & Exploration

- Dataset structure and inspection with `pandas`
- Descriptive statistics: mean, median, mode, variance, std deviation
- Visual exploration using histograms, boxplots, violin plots, pairplots

### Statistical Inference

- Two-sample t-tests
- Confidence intervals
- Insights into feature differences between species

### Machine Learning

- Feature selection and model training
- Logistic Regression, K-Nearest Neighbors, Decision Tree
- Evaluation with accuracy, confusion matrix, and classification report
- 5-fold cross-validation for generalization

### Key Results

- **Best feature for classification:** petal length & petal width
- **Highest accuracy:** Logistic Regression (97%) and KNN (97%) on test set
- **Setosa** is perfectly separable; Versicolor and Virginica overlap slightly
- Visual and statistical insights are consistent

---

**Source:**  
Dataset from Seaborn: [iris.csv](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv)

## Installation & Environment Setup

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
