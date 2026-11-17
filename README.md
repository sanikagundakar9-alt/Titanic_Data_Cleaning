# 🚢 Titanic Survival Prediction – Data Cleaning Project

## 📌 Project Overview
This project is part of my Machine Learning & AI Internship – Week 1.

The objective of this project is to perform data cleaning and preprocessing on the Titanic dataset using Python. It includes handling missing values, encoding categorical variables, visualizing data, and exporting the cleaned dataset into a CSV file.

## 🎯 Objectives
- Load and explore the Titanic dataset using Pandas.
- Understand dataset information using `.info()` and `.describe()`.
- Identify and handle missing values using Mean, Median, and Mode imputation.
- Encode categorical variables using LabelEncoder and OneHotEncoder.
- Visualize passenger age distribution using Matplotlib and Seaborn.
- Export the cleaned dataset into a new CSV file.

## 🛠️ Technologies & Libraries Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Project Structure

```text
Titanic_Data_Cleaning/
│
├── Titanic-Dataset.csv
├── Titanic_Data_Cleaning.ipynb
├── cleaned_titanic.csv
└── README.md
```

## ⚙️ Project Implementation

### 1. Data Loading and Exploration
- Loaded the Titanic dataset using Pandas.
- Used `.head()` to display the first five records.
- Used `.info()` to understand data types and missing values.
- Used `.describe()` to generate statistical summaries.

### 2. Handling Missing Values
- Age: Filled missing values using Median.
- Embarked: Filled missing values using Mode.
- Fare: Filled missing values using Median.
- Cabin: Removed the column due to excessive missing values.

### 3. Categorical Encoding
- Used LabelEncoder to convert Sex categories into numerical values.
- Used OneHotEncoder to encode the Embarked column.

### 4. Data Visualization
- Visualized passenger age distribution using Matplotlib.
- Created a histogram using Seaborn.
- Used KDE to display the age distribution curve.

### 5. Exporting Cleaned Dataset
- Exported the processed dataset into `cleaned_titanic.csv`.
- Verified the cleaned dataset.

## 📊 Expected Outcomes
- Successfully loaded and explored the Titanic dataset.
- Handled missing values.
- Converted categorical variables into numerical format.
- Visualized age distribution.
- Generated a cleaned CSV dataset.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Open the project folder in VS Code.
4. Open `Titanic_Data_Cleaning.ipynb`.
5. Run all notebook cells.
6. Check the generated `cleaned_titanic.csv` file.

## 🎓 Learning Outcomes
Through this project, I learned:
- Data loading and exploration using Pandas.
- Data preprocessing and missing value handling.
- Categorical data encoding.
- Data visualization.
- Exporting processed datasets.

## 👩‍💻 Internship Details
**Internship:** Machine Learning & AI Internship  
**Organization:** SkillNexis  
**Module:** Week 1  
**Project:** Titanic Survival Prediction – Data Cleaning Project

---

**Status:** Completed ✅
