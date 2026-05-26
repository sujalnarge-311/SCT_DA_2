# SCT_DA_2

Data Cleaning and Preparation using Python Pandas | SkillCraft Technology Internship

## Project Overview
This project focuses on Data Cleaning and Preparation using Python and Pandas on the Global Superstore dataset. The main objective was to clean raw data, handle missing values, remove unnecessary columns, convert data types, and perform basic feature engineering to prepare the dataset for analysis.

---

## Objectives
- Load and explore the dataset
- Check dataset structure and statistics
- Handle missing values
- Remove unnecessary columns
- Rename columns for better readability
- Convert columns into appropriate data types
- Perform feature engineering
- Export cleaned dataset

---

## Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Dataset Information
The dataset contains:
- Customer details
- Product details
- Sales records
- Profit information
- Shipping details
- Regional sales information

---

## Steps Performed

### 1. Data Loading
Imported the dataset into Jupyter Notebook using Pandas.

### 2. Data Exploration
- Viewed dataset using `head()`
- Checked dataset shape
- Analyzed column names
- Generated statistical summary using `describe()`

### 3. Data Cleaning
- Checked missing values
- Removed null values using `dropna()`
- Checked duplicate records
- Removed unnecessary columns

### 4. Column Renaming
Renamed columns for better readability:
- `Sub.Category` → `Sub_Category`
- `Order.Date` → `Order_Date`
- `Ship.Date` → `Ship_Date`

### 5. Data Type Conversion
Converted:
- `Order_Date` and `Ship_Date` into datetime format
- Categorical columns into category datatype

### 6. Feature Engineering
Created new columns:
- `Sales_Category`
- `Profit_Status`

### 7. Data Export
Exported the cleaned dataset into a new CSV file.

---

## Project Files
- `superstore.csv` → Original Dataset
- `Cleaned_Global_Superstore.csv` → Cleaned Dataset
- `SCT_DA_2.ipynb` → Jupyter Notebook
- `README.md` → Project Documentation

---

## Outcome
Successfully cleaned and transformed the dataset into an analysis-ready format suitable for:
- Data Analysis
- Dashboard Creation
- Business Insights
- Visualization Projects

---

## Skills Gained
- Data Cleaning
- Data Preparation
- Data Transformation
- Feature Engineering
- Python Programming
- Pandas Library
- Jupyter Notebook

---

## Author
Sujal Narge
