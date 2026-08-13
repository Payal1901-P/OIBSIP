# Iris Flower Classification

## OASIS INFOBYTE - Data Science Internship

### Task 1: Iris Flower Classification

## Project Overview

This project focuses on classifying Iris flowers into three different species:

- Setosa
- Versicolor
- Virginica

The Iris dataset is analyzed using Exploratory Data Analysis (EDA), data visualization, and machine learning classification algorithms.

## Dataset

The Iris dataset is loaded directly using the `scikit-learn` library.

The dataset contains 150 samples and four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

There are three target classes:

- Setosa
- Versicolor
- Virginica

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Exploratory Data Analysis

The following EDA techniques were performed:

- Dataset shape and data type analysis
- Missing-value checking
- Statistical summary
- Species distribution visualization
- Pairplot
- Box plots

## Feature Selection

Based on the exploratory analysis and visualizations, petal length and petal width were found to be particularly useful for distinguishing the three Iris species.

## Machine Learning Models

Two classification algorithms were implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| K-Nearest Neighbors | 100% |

Based on the test-set accuracy, K-Nearest Neighbors (KNN) performed better than Logistic Regression on this dataset.

## Conclusion

The Iris flower classification project successfully demonstrates the complete machine learning workflow, including data exploration, visualization, feature analysis, model training, and evaluation.

K-Nearest Neighbors was selected as the best-performing model among the two models tested.

## Project File

The main project notebook is:

`Iris_Classification.ipynb`
