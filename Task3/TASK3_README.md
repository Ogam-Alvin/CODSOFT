# Iris Dataset Classification with Machine Learning
## Overview
This project applies machine learning models to the Iris dataset to predict the species of flowers based on measurements of their sepals and petals. The dataset is explored using descriptive statistics, visualizations, and data preprocessing techniques. The models used include Logistic Regression, Decision Tree, Support Vector Machine (SVM), and Random Forest, with hyperparameter tuning performed via GridSearchCV to enhance their performance.

## Project Steps
## Data Preprocessing:

1. Explored the dataset using .describe(), .info(), and .isnull() to understand its structure and handle missing or duplicate data.
Standardized numerical columns using StandardScaler and encoded categorical values with LabelEncoder.
Exploratory Data Analysis (EDA):

2. Visualized species counts and relationships between features using bar plots and scatter plots.
Used pairplots to assess the interaction between different features.

3. Model Training and Evaluation:
- Split the data into training and testing sets.
- Trained Logistic Regression, Decision Tree, SVM, and Random Forest classifiers.
- Evaluated models using accuracy and classification reports, highlighting performance on both training and test sets.
- Hyperparameter Tuning:

Optimized each model's performance using GridSearchCV to find the best hyperparameters, improving generalization and reducing overfitting.

## Results
- Logistic Regression: High accuracy (97% test) with balanced precision and recall.
- Decision Tree: Overfitting without tuning, with reduced accuracy on the test set (92%).
- SVM: Strong performance (95% test accuracy) with balanced metrics across classes.
- Random Forest: Overfitting without tuning, but after tuning, it showed good performance (95% test accuracy).

## Conclusion
SVM and tuned Random Forest provided the best balance between training and test performance. Decision Trees, while performing well on the training set, required tuning to avoid overfitting. This project highlights the importance of hyperparameter tuning to improve model generalization.

## Files
1. IRIS.csv: The Iris dataset used in this analysis.
2. iris_classification.ipynb: Jupyter notebook containing all the code for EDA, model training, and evaluation.

## Requirements
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Future Improvements
- Experiment with more advanced classification algorithms like Gradient Boosting.
- Explore feature engineering to enhance model accuracy.