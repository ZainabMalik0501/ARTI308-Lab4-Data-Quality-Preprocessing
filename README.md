# Lab 4 - Data Quality Assessment & Preprocessing
**ARTI 308 - Machine Learning**

## Dataset
- **Name**: Chocolate Sales Dataset  
- **File**: `Chocolate_Sales.csv`  
- **Description**: Sales records of various chocolate products across multiple countries (2022–2024).  
- **Columns**: Sales Person, Country, Product, Date, Amount, Boxes Shipped

## Tasks Completed

### Task 1: Identify Data Quality Issues
- Detected incorrect data types (`Date` and `Amount` were stored as object)
- Checked for missing values and duplicates
- Identified possible outliers in `Amount` and `Boxes Shipped`

### Task 2: Handling Missing Values
- Created artificial missing values for demonstration
- Applied **Mean Imputation** on the `Amount` column (best for numerical sales data)

### Task 3: Outlier Detection & Handling
- Used **IQR method** to detect outliers
- Handled outliers using **capping (Winsorization)**

### Task 4: Feature Normalization
- Applied **Min-Max Normalization** (scales values to 0–1)
- Applied **Z-score Standardization**

### Task 5: Principal Component Analysis (PCA)
- Confirmed high correlation between `Amount` and `Boxes Shipped`
- Reduced dimensionality to 2 components using PCA
- Visualized the PCA projection

## Visualizations Included in the Notebook
- Amount vs Boxes Shipped scatter plot  
- Boxplot after outlier handling  
- PCA 2D projection

## Notebook
[chocolate_sales_preprocessing.ipynb](chocolate_sales_preprocessing.ipynb)

---

**Submitted by:** Zainab Malik  
**Date:** April 2026
