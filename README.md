# Marketing-Analytics
## Project Overview
This project aims to analyze customer data to derive insights for enhancing marketing strategies. The analysis includes data preprocessing, visualization, and modeling to understand customer behavior and demographics.

## Key Steps
### 1.Data Loading and Preprocessing

  Loaded dataset from an Excel file.

  Handled missing values using mean or mode.

  Encoded categorical features into numerical values.

### 2.Data Visualization and Insights

  Histograms: Highlighted distribution and potential skewness of numerical features.

  Box Plot for LoyalTime: Identified outliers, central tendency, and variability.

  Correlation Matrix: Explored relationships between features:

    Positive correlation: DemAffl and TargetBuy.

    Negative correlation: DemAge and LoyalClass.

  Count Plots: Showed distribution of DemGender and LoyalClass.

  Scatter Plot between LoyalTime and DemAge: Illustrated relationship, showing general patterns.

### 3.Feature Encoding

  Converted categorical features to numerical values for modeling.

### 4.Modeling and Evaluation

  Trained a Logistic Regression model.

  Evaluated performance with a 70% accuracy score.

  Suggested improvements: feature engineering, hyperparameter tuning, trying different models.

## Technologies Used
  Python 
  pandas
  numpy
  matplotlib
  seaborn
  scikit-learn

## How to Use
  Clone the repository.

  Navigate to the notebooks/ directory.

  Open the Jupyter notebooks to explore the analysis and findings.

  Use the scripts for data processing and model training.
 
 ## Conclusion
The project provided valuable insights into customer demographics and behavior, informing targeted marketing strategies and customer segmentation. Visualizations and analyses highlighted key patterns and relationships, setting the stage for further analysis and improvements in predictive modeling.
