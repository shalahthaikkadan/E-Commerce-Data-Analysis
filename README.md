# Project 1: Advanced EDA & Feature Engineering

## 📌 Overview

This project was completed as part of the **DecodeLabs Industrial Training Kit 2026 – Data Science**.

The objective is to transform a raw e-commerce dataset into a clean, machine-learning-ready dataset by performing Exploratory Data Analysis (EDA), data cleaning, outlier treatment, feature engineering, and categorical encoding.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Handle missing values
- Detect and treat outliers
- Engineer new predictive features
- Encode categorical variables
- Prepare the dataset for machine learning
- Export the cleaned dataset

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```
project1-eda/
│
├── Dataset for Data Analytics - Sheet1.csv      # Original dataset
├── Cleaned_Ecommerce_Dataset.csv                # Cleaned dataset
├── eda_project1.ipynb                           # Jupyter Notebook
├── README.md
└── .gitignore
```

---

## 📊 Dataset Information

### Original Dataset

- Rows: 1200
- Columns: 14
- Contains missing values
- Contains categorical and numerical features

### Final Dataset

- Rows: 1200
- Columns: 47
- Missing values removed
- New features created
- Categorical variables encoded
- Ready for machine learning

---

## 🔍 Project Workflow

### 1. Data Loading

- Imported CSV using Pandas
- Displayed dataset information

### 2. Exploratory Data Analysis (EDA)

- Checked dataset shape
- Inspected data types
- Generated descriptive statistics
- Identified missing values

### 3. Missing Value Handling

Missing values were handled using appropriate replacement techniques for selected columns.

---

### 4. Outlier Detection

Outliers were identified using the Interquartile Range (IQR) method.

---

### 5. Outlier Treatment

Extreme values were capped using the IQR boundaries.

---

### 6. Feature Engineering

Created new features including:

- AveragePricePerItem
- CouponUsed
- OrderMonth
- Weekday

---

### 7. Categorical Encoding

Applied One-Hot Encoding to categorical columns such as:

- Product
- PaymentMethod
- OrderStatus
- ReferralSource
- OrderMonth
- Weekday

---

### 8. Correlation Analysis

Generated a correlation heatmap to analyze relationships among numerical features.

---

### 9. Export

Saved the processed dataset as:

```
Cleaned_Ecommerce_Dataset.csv
```

---

## 📈 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Outlier Detection
- Missing Value Handling
- Data Visualization
- Data Preprocessing
- Python Programming

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/shalahthaikkadan/decode-lab.git
```

2. Navigate to the project folder

```bash
cd decode-lab
```

3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all notebook cells.

---

## 📌 Project Outcome

The raw dataset was successfully transformed into a clean and structured dataset suitable for machine learning applications through EDA, preprocessing, feature engineering, and encoding.

---

## 👨‍💻 Author

**Mohammad Shalah**

GitHub: https://github.com/shalahthaikkadan

---

## ⭐ Acknowledgement

This project was completed as part of the **DecodeLabs Industrial Training Kit 2026 – Data Science**.
