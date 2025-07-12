# Deliverable 1: Data Collection, Cleaning, and Exploration

## Dataset Summary

This project uses the Stroke Prediction Dataset from Kaggle. I chose this dataset because it is rich with both clinical and demographic features, making it perfect for data mining tasks like classification, EDA, and predictive modeling. The dataset contains 5,110 records and 11 attributes, including both demographic and health-related features. The target variable is `stroke`, which indicates whether a patient has experienced a stroke (1 = Yes, 0 = No).

Key features include:  
- gender  
- age  
- hypertension  
- heart_disease  
- ever_married  
- work_type  
- Residence_type  
- avg_glucose_level  
- bmi  
- smoking_status

## Steps Taken

### Data Cleaning
- Missing values in the `bmi` column were handled using median imputation.
- Duplicate rows were removed.
- Inconsistent values such as "Other" in the `gender` column were identified and removed for clarity.

### Data Exploration (EDA)
- Distributions of numerical features such as age, BMI, and glucose levels were visualized using histograms and boxplots.
- Relationships between features and the stroke target variable were explored using boxplots and countplots.

## Key Insights
- Older age and higher glucose levels appear to be associated with stroke cases.
- Work type and other categorical variables may contribute to stroke likelihood and should be included in future modeling.

## Challenges
- Class imbalance: The dataset has a significantly higher number of non-stroke cases than stroke cases. This may require balancing techniques during modeling.
- Missing values: The `bmi` column had missing data that needed to be addressed.

## Files Included
- `Deliverable1.ipynb`: A Jupyter Notebook with all code, visualizations, and comments explaining each step.
- `README.md`: This file, which summarizes the dataset, steps taken, insights gained, and challenges encountered.

