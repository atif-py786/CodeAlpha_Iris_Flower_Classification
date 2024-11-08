# Iris Flower Classification Project 🌸

## Overview

This project focuses on classifying iris flowers into three species (Setosa, Versicolor, and Virginica) based on sepal and petal dimensions. The Iris dataset is widely used in machine learning for classification problems, making it an ideal choice for practicing data analysis, feature engineering, and classification model building.

## Dataset Information

The **Iris dataset** contains 150 samples of iris flowers, with the following features:

- **Sepal Length**: Length of the sepal (cm)
- **Sepal Width**: Width of the sepal (cm)
- **Petal Length**: Length of the petal (cm)
- **Petal Width**: Width of the petal (cm)
- **Species**: The species of the iris flower (Setosa, Versicolor, Virginica)

The dataset is small yet insightful, with clearly distinguishable classes, making it suitable for practicing classification.

---

## Project Workflow

The project workflow follows a structured approach:

1. **Data Collection & Loading**: Load the dataset and check for missing or inconsistent data.
2. **Data Exploration & Visualization**: Explore data relationships and identify potential patterns.
3. **Data Preprocessing**: Clean, scale, and prepare data for modeling.
4. **Feature Selection**: Identify key features for efficient classification.
5. **Model Building**: Develop and compare multiple machine learning models.
6. **Model Evaluation**: Evaluate models using metrics such as accuracy, precision, and recall.
7. **Conclusions & Insights**: Draw insights from the model and project results.

---

## Exploratory Data Analysis (EDA)

The EDA phase is essential to understand data distributions and relationships:

1. **Descriptive Statistics**: Calculated means, standard deviations, and distributions for each feature.
2. **Data Visualization**:
    - **Pair Plot**: Visualized pairwise relationships between features using Seaborn’s pair plot. Clear separability between species was observed, especially Setosa.
    - **Box Plots**: Analyzed the spread of each feature across species, highlighting outliers and ranges.

These visualizations provided initial insights into how features like petal length and petal width are more effective in differentiating species.

---

## Feature Engineering

Feature engineering involved the following:

1. **Feature Scaling**: Standardized features to ensure all are on the same scale.
2. **Feature Selection**: Although all features were used, emphasis was placed on petal length and width, which were most significant for classification based on the visual separability observed during EDA.

---

## Model Building

Several classification models were tested to compare their performance:

1. **Logistic Regression**: Used as a baseline model for its simplicity and interpretability.
2. **K-Nearest Neighbors (KNN)**: Tested multiple `k` values to find optimal neighbors for classification accuracy.
3. **Decision Tree Classifier**: Built with various depths, providing intuitive branching logic that fits well with this dataset.
4. **Support Vector Classifier (SVC)**: Explored linear and non-linear kernels to enhance decision boundaries.

---

## Model Evaluation

In this project, all the models tested—including **Logistic Regression**, **K-Nearest Neighbors (KNN)**, **Decision Tree** and **Support Vector Classifier (SVC)** achieved **100% accuracy** on the dataset. This exceptional performance across models can be attributed to:

1. **Clear Class Separability**: The Iris dataset has well-separated classes, especially in petal dimensions, making it straightforward for classification algorithms to distinguish between species.
2. **Balanced Data**: Each species has an equal number of samples (50 per class), minimizing class imbalance issues.
3. **Effective Features**: Features like petal length and petal width are highly predictive of species, contributing to the high accuracy of all models.


---

## Conclusion

With all models achieving **perfect accuracy**, the Iris Flower Classification project underscores the power of well-structured datasets in model training. This project provided valuable experience in:

- Working with classic classification datasets.
- Understanding the importance of feature selection.
- Learning how model performance can vary based on data complexity.

This project enhanced my understanding of model selection, evaluation metrics, and visualization techniques for small datasets.
