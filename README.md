# Titanic Dataset – Task 1: Data Cleaning and Preprocessing 🚢

This project is part of the internship task to perform **data cleaning and preprocessing** on the Titanic dataset. The goal is to prepare the dataset for further machine learning tasks by handling missing values, encoding categorical variables, scaling features, and identifying outliers.

---

## 📁 Dataset Description

The dataset contains information about Titanic passengers, including:
- Demographics (Name, Sex, Age)
- Ticket details (Pclass, Fare, Ticket)
- Survival status (`Survived`)

---

## 🔧 Tasks Performed

### 1. 📥 Import and Inspect
- Loaded the dataset using `pandas`
- Displayed column types and summary using `.info()` and `.describe()`

### 2. ❌ Missing Value Handling
- **Age**: Filled with median
- **Embarked**: Filled with mode
- **Cabin**: Dropped due to excessive missing values

### 3. 🔤 Categorical Encoding
- `Sex` and `Embarked` were encoded using **LabelEncoder**

### 4. 📏 Feature Scaling
- Scaled `Age` and `Fare` columns using **StandardScaler**

### 5. 📊 Outlier Detection & Removal
- Used **boxplots** to visualize outliers
- Removed rows with outliers beyond **3 standard deviations**

### 6. 💾 Saved Cleaned Dataset
- Exported the final cleaned dataset as `cleaned_titanic.csv`

---

## 📊 Visualizations

- Boxplots for Age and Fare
- Value counts of categorical columns (optional)

---

## 💡 Key Learnings

- Identifying and handling missing data is crucial
- Label encoding simplifies categorical data
- Scaling helps normalize feature ranges
- Outlier detection improves model accuracy

---

## 📂 Files Included

| File Name             | Description                       |
|----------------------|-----------------------------------|
| `titanic_cleaning.ipynb` | Main notebook with all steps      |
| `cleaned_titanic.csv`    | Final cleaned dataset             |
| `README.md`               | This readme file                 |

---

## ❓ Common Interview Questions Covered

1. What are types of missing data?  
2. How do you handle categorical variables?  
3. Difference between normalization and standardization  
4. Outlier detection methods  
5. Why is preprocessing important before modeling?

---
Then run the notebook or Python file.

## 🚀 How to Run

```bash
pip install pandas numpy seaborn scikit-learn matplotlib
```

---

## 👤 Author

Name: Sai Gulve  
Internship Task: Aiml Internshp – Task 1  
Date: [Add Date]
```
