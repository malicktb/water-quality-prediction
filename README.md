# Water Quality Prediction

This project aims to predict water potability using machine learning models applied to the Kaggle Water Quality dataset. The objective is to compare different models to identify the most effective approach for classifying water as potable or non-potable.

## Project Overview

The availability of safe drinking water is crucial for public health. This project leverages the Kaggle Water Quality dataset to build and evaluate various machine learning models, providing insights into which model best predicts water potability. The dataset includes various physicochemical properties of water samples, and the goal is to classify these samples based on their potability status.

## Dataset

- **Source:** [Kaggle Water Quality Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
)
- **Description:** The dataset contains measurements of different water quality parameters and their corresponding potability status.

## Models Implemented

1. **XGBoost Classifier**  
2. **Random Forest Classifier**  
3. **Multilayer Perceptron (MLP) Classifier**  
4. **Decision Tree Classifier**  
5. **Gaussian Naive Bayes Classifier**

## Key Techniques

- **Data Analysis & Visualization:** Utilized Seaborn and Matplotlib for exploring feature relationships and visualizing data distributions.
- **Model Evaluation:** Applied hyperparameter tuning, KFold cross-validation, and evaluated models using accuracy, precision, recall, and F1 score metrics.
- **Feature Engineering:** Analyzed feature importance to identify key factors influencing water potability.

## Results

- **Best Performing Model:** Random Forest Classifier with 80% accuracy.
- **Other Notable Models:** XGBoost Classifier with 78% accuracy, and MLP Classifier with 69% accuracy.
- **Least Effective Model:** Gaussian Naive Bayes.
