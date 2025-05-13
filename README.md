# Cancer Survival Prediction using Random Forest

## Summary

In this study, we performed data analysis, cleaning, visualization, and machine learning (ML) modeling on a colorectal cancer dataset. The workflow consisted of the following steps:

### 1. Data Exploration and Cleaning
- Loaded data from `colorectal_cancer_dataset.csv`.
- Removed missing values and irrelevant columns.
- Standardized text and binary categorical variables.
- Encoded categorical variables and removed duplicates.

### 2. Data Visualization
Generated 12+ insightful visualizations:
- Age & tumor size (Histogram, KDE, Boxplot)
- Gender & cancer stage (Countplot, Pie chart)
- Lifestyle factors vs. stage (Countplots)
- Economic factors vs. survival (Violin, Bar plots)
- Correlation heatmap, Age-based incidence trends

### 3. Machine Learning Model for Prediction
- Target: `Survival_5_years` (binary classification)
- Used LabelEncoder, StandardScaler, train_test_split
- Trained a Random Forest Classifier
- Evaluated with accuracy, classification report, confusion matrix

### 4. Visualization of Model Results
- Confusion matrix
- Feature importance
- Actual vs. Predicted survival scatter plot

## Final Outcome
This end-to-end ML pipeline predicted 5-year survival for colorectal cancer patients and evaluated results with strong performance metrics and visual insights.

👉 Dataset used:  
[Colorectal Cancer Dataset](https://github.com/Mosaad2010-star/cancer-survival-prediction-random-forest/blob/main/colorectal_cancer_dataset.csv)
