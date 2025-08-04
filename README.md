# AI & ML Internship - Task 1: Data Cleaning & Preprocessing

## Overview
This repository contains the solution for Task 1 of the Elevate AI & ML Internship. The goal of this task was to learn how to clean and prepare raw data for machine learning models using Python and common data science libraries.

## Dataset
The Titanic dataset was used for this task. It contains information about passengers, including demographic and travel details, along with their survival status.

## Tools and Libraries Used
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for preprocessing utilities)

## Task Steps
1. **Import and Explore Data:**  
   Loaded the dataset and explored its structure and missing values.

2. **Handle Missing Values:**  
   Imputed missing numerical data (Age, Fare) with median/mean and categorical data (Embarked) with mode.

3. **Encode Categorical Variables:**  
   Converted categorical columns (`Sex`, `Embarked`) into numerical format using label encoding and one-hot encoding.

4. **Normalize/Standardize Features:**  
   Standardized numerical columns (Age, Fare) for uniform scale.

5. **Outlier Detection and Removal:**  
   Visualized outliers with boxplots and removed them using the Interquartile Range (IQR) method.

## How to Run
- Ensure all dependencies are installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
- Run the provided Python script or Jupyter notebook.
- The cleaned dataset will be saved as `titanic_cleaned.csv`.

## What I Learned
- The importance of handling missing data before modeling.
- Different methods for encoding categorical variables and why they matter.
- Feature scaling techniques and their impact on model performance.
- How to identify and handle outliers using visualization and statistical methods.

## Submission
This repository is submitted as part of the Elevate AI & ML Internship Task 1.

Thank you for reviewing my work!

