# 🧹 Titanic Dataset – Data Cleaning & Preprocessing

## 📌 Objective
The goal of this task is to clean and preprocess the Titanic dataset to make it suitable for machine learning.

---

## 📁 Dataset
- **Source**: [Kaggle – Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **File used**: `titanic.csv`

---

## 🛠 Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (StandardScaler)
- SciPy (for Z-score outlier detection)

---

## ✅ Steps Performed

### 1. Data Loading
Loaded the Titanic dataset using `pandas`.

### 2. Initial Exploration
Checked data types, null values, and descriptive statistics.

### 3. Handling Missing Values
- Filled missing values in `Age` with **median**
- Filled missing values in `Embarked` with **mode**
- Dropped `Cabin` column due to too many missing values

### 4. Encoding Categorical Features
- Applied **One-Hot Encoding** on `Sex` and `Embarked`
- Dropped: `Name`, `Ticket`, `PassengerId`

### 5. Feature Scaling
- Scaled `Age` and `Fare` using **StandardScaler**

### 6. Outlier Detection & Removal
- Visualized outliers using **boxplots**
- Removed extreme outliers using **Z-score method** (|Z| > 3)

### 7. Export Cleaned Data
- Final cleaned data saved as `titanic_cleaned.csv`

---

## 📊 Final Dataset
- ✅ Total rows after outlier removal: **`[fill in number, e.g., 875]`**
- 📈 All features are numeric and ready for ML

---

## 📂 Files Included
- `titanic_preprocessing.ipynb` – Notebook with all preprocessing steps
- `titanic_cleaned.csv` – Cleaned and scaled dataset
- `README.md` – Project documentation

---
