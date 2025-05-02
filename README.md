# Iris Flower Classification Model

## Problem Statement
The goal of this project is to build an Iris Flower Classification Model that predicts the species of Iris flowers based on their sepal length, sepal width, petal length, and petal width. This model will help in identifying the species of the flower, aiding in agricultural studies and botanical research.

## About the Dataset
The dataset used for this project is the **Iris Flower Dataset**, which contains various attributes of Iris flowers. The data provides insight into how flower features such as petal and sepal dimensions correlate with species. This dataset is publicly available and widely used for classification tasks in machine learning.

### Dataset Information:
- **Source**: UCI Machine Learning Repository (Iris Flower Dataset)
- **Rows**: 150
- **Columns**: 5

### Features:
The dataset consists of the following columns:

- **Sepal Length**: The length of the sepal (numeric)
- **Sepal Width**: The width of the sepal (numeric)
- **Petal Length**: The length of the petal (numeric)
- **Petal Width**: The width of the petal (numeric)
- **Species**: The target variable representing the species of the Iris flower (categorical: 'Setosa', 'Versicolor', 'Virginica')

## Why This Dataset?
This dataset is ideal for classification problems because it includes distinct features that can be used to classify the flower species. The dataset is also small enough to experiment with, making it perfect for beginners in machine learning.

### Benefits of this dataset:
- It provides clear and well-defined features for classification.
- It is widely used, making it a great resource for learning.
- It is easy to handle and quick to train a model on, making it a good starter project for machine learning enthusiasts.

## Model
The model used for this project is a **Logistic Regression** classifier, which is suitable for multi-class classification tasks. The model will predict the species of the Iris flower based on the input features.

### Steps Taken:

1. **Data Preprocessing**:
    - Handled missing values (if any) and scaled the numerical features (sepal and petal measurements) to standardize them.
    
2. **Model Training**:
    - Trained a Logistic Regression model on the preprocessed dataset and evaluated its performance using cross-validation.

3. **Model Evaluation**:
    - Evaluated the model’s performance using metrics like accuracy, precision, recall, and F1-score.

4. **Model Saving**:
    - The trained model was saved as a pickle file (`model.pkl`) for future use, such as making predictions on new data.

## About
A machine learning project that predicts the species of Iris flowers using features like sepal length, sepal width, petal length, and petal width. The model classifies the species as 'Setosa', 'Versicolor', or 'Virginica' using Logistic Regression and evaluates its accuracy.

## Topics
- python
- machine-learning

## Resources
- UCI Machine Learning Repository (Iris Flower Dataset)
- Scikit-learn (Logistic Regression)

## Languages
- **Jupyter Notebook**: 91.3%
- **Python**: 8.7%
