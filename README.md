# Weather-Data-Exploratory-Data-Analysis-using-Python

This project focuses on end to end data cleaning and exploratory data analysis (EDA) on a weather dataset. The objective was to convert raw, inconsistent weather data into a clean, analysis ready dataset and extract meaningful insights using Python.

---

## Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Dataset Overview

- Records: 158
- Features include:
   - Ozone levels
   - Solar radiation
   - Wind speed
   - Temperature
   - Weather conditions
   - Date related attributes

---

## Project Workflow

### 1. Data Loading

- Loaded CSV dataset
- Checked shape, data types, and summary statistics
- Identified missing values and duplicate records

### 2. Data Cleaning

- Removed duplicate rows
- Dropped irrelevant columns
- Renamed columns for clarity
- Handled missing values using mean imputation
- Standardized categorical values (Month column)

### 3. Feature Engineering

- Created a unified Date column using Year, Month, and Day
- Converted data into analysis friendly formats

### 4. Outlier Detection

- Identified outliers in Ozone levels using the IQR method
- Retained outliers as they may represent real extreme weather conditions

### 5. Exploratory Data Analysis (EDA)

- Distribution analysis for numerical features
- Weather wise and monthly comparisons
- Scatter plots and correlation heatmap
- Time series analysis of temperature trends
- Grouped analysis by weather conditions

### 6. Business Insights

- Average weather conditions by category
- Temperature trends across months
- Wind and ozone behavior under different weather patterns

---

## Key Outcomes

- Cleaned and structured a raw weather dataset
- Performed comprehensive EDA
- Generated actionable insights from weather patterns
- Created a reusable analysis ready dataset

---

## Author
 
LinkedIn: www.linkedin.com/in/abhaypandey18
