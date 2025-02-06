# Airline Passenger Satisfaction - Classification Analysis

## Overview
This project analyzes the "Airline Passenger Satisfaction" dataset using classification techniques. It involves data cleaning, exploratory data analysis, and classification using Random Forest. Additionally, dimensionality reduction techniques such as PCA and t-SNE are applied to enhance model efficiency and visualization.

## Dataset
- Source: Kaggle ([teejmahal20/airline-passenger-satisfaction](https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction))
- The dataset contains passenger details and their satisfaction ratings.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- pydot
- kagglehub

## Steps in the Project
### 1. Data Cleaning and Exploration
- Load dataset using `kagglehub`
- Remove missing values and duplicates
- Drop unnecessary columns (`id`, `Unnamed: 0`)
- One-hot encode categorical variables
- Visualize feature correlations using a heatmap

### 2. Data Splitting
- Select features (`X`) and target variable (`y`)
- Split data into training (70%) and testing (30%) sets

### 3. Classification with Random Forest
- Train a `RandomForestClassifier` model
- Evaluate performance using:
  - Accuracy score
  - Confusion matrix
  - Classification report
  - Matthews Correlation Coefficient (MCC)

### 4. Dimensionality Reduction
#### Principal Component Analysis (PCA)
- Apply PCA to reduce feature dimensions
- Evaluate the model's performance with different numbers of components
- Visualize the first two principal components

#### t-SNE Visualization
- Apply t-SNE to visualize high-dimensional data in a 2D space
- Scatter plot to compare satisfied vs. unsatisfied passengers


## Results
- Random Forest achieved high classification accuracy.
- PCA reduced dimensionality while maintaining classification performance.
- t-SNE provided an insightful visualization of data distribution.

## Future Improvements
- Experiment with other classifiers (e.g., SVM, XGBoost)
- Hyperparameter tuning for better performance
- Feature engineering to improve classification accuracy

