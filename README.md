# Material_Strength

---

# Project Title

**Predicting Material Strength with Machine Learning**

## Overview

This project aims to predict material strength using machine learning techniques. The dataset used in this project contains various features related to cement properties and age, and the target variable is material strength. The goal is to build a predictive model that can accurately estimate material strength based on these features.

## Dataset

The dataset used in this project consists of the following columns:

- `cement`: Amount of cement used.
- `blast_furnace_slag`: Amount of blast furnace slag used.
- `fly_ash`: Amount of fly ash used.
- `water`: Amount of water used.
- `superplasticizer`: Amount of superplasticizer used.
- `coarse_aggregate`: Amount of coarse aggregate used.
- `fine_aggregate`: Amount of fine aggregate used.
- `age`: Age of the material.
- `Material Strength`: The target variable, material strength.

## Data Analysis

- Checked for outliers in the dataset.
- Explored the correlation between features.
- Visualized the data using QQ plots, box plots, and histograms with KDE (Kernel Density Estimation) plots.

## Data Preprocessing

- Scaled the data to ensure all features are on the same scale.
- Applied power transformation to address skewness in the data.

## Machine Learning Models

The following machine learning models were implemented and evaluated:

1. Linear Regression
2. Ordinary Least Squares (OLS) Model
3. K-Nearest Neighbors (KNN)
4. Gradient Descent (Custom Implementation)

## Model Evaluation

Based on model evaluation metrics, including the R-squared (R2) score, the K-Nearest Neighbors (KNN) model performed the best with an R2 score of 0.82. This indicates that the KNN model provides a good fit for predicting material strength.





