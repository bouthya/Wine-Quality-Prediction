# Wine Quality Prediction

## Project Overview

Wine Quality Prediction is a machine learning project that focuses on predicting the quality of wine based on its chemical characteristics. The project applies multiple classification algorithms to analyze how different chemical properties influence wine quality and compares model performance.

## Objectives

* Load and explore the wine quality dataset.
* Perform data cleaning and preprocessing.
* Analyze chemical properties affecting wine quality.
* Train multiple classification models.
* Compare model performance using evaluation metrics.
* Visualize patterns and relationships within the dataset.
* Generate insights and recommendations.

## Dataset Information

The dataset contains various chemical attributes of wine samples, including:

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality (Target Variable)

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Models Used

### 1. Random Forest Classifier

* Ensemble learning algorithm.
* Handles complex relationships effectively.
* Provides feature importance analysis.

### 2. Stochastic Gradient Descent (SGD) Classifier

* Efficient for large datasets.
* Fast model training and prediction.

### 3. Support Vector Classifier (SVC)

* Effective for classification tasks.
* Works well with high-dimensional feature spaces.

## Project Workflow

### 1. Data Collection

* Load the wine quality dataset.
* Understand dataset structure and features.

### 2. Data Cleaning

* Check for missing values.
* Remove duplicate records.
* Prepare data for analysis.

### 3. Exploratory Data Analysis (EDA)

* Analyze quality distribution.
* Study feature relationships.
* Generate correlation heatmaps.
* Visualize feature distributions.

### 4. Feature Engineering

* Select relevant features.
* Scale numerical variables using StandardScaler.

### 5. Model Training

* Split dataset into training and testing sets.
* Train Random Forest, SGD, and SVC models.

### 6. Model Evaluation

Evaluate model performance using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 7. Visualization

* Wine Quality Distribution
* Correlation Heatmap
* Confusion Matrix
* Feature Importance Plot
* Model Comparison Chart

## Key Findings

* Alcohol content is one of the strongest predictors of wine quality.
* Sulphates positively influence wine quality.
* Volatile acidity negatively impacts quality ratings.
* Random Forest generally provides the highest classification accuracy.

## Business Recommendations

1. Monitor alcohol levels during production.
2. Optimize sulphate concentration to improve quality.
3. Reduce excessive volatile acidity.
4. Use predictive models for quality control before product release.
5. Implement data-driven quality assessment procedures.

## Results

The project demonstrates how machine learning can be applied to predict wine quality using chemical characteristics. Multiple classification models were evaluated, and the best-performing model was identified for accurate wine quality prediction.

## Author

**Bouthya Battu**
