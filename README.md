# Mushroom Classification Task

### Introduction

This repository contains the implementation of Task 3 - Mushroom Classification, as part ofmy Masters degree. The task involves utilizing a provided dataset to classify mushrooms as either Poisonous or Edible based on their features.

### Dataset Overview

The dataset consists of various features describing different attributes of mushrooms, with the target variable indicating whether the mushroom is Poisonous (p) or Edible (e).
### Steps Implemented

1. **Data Import and Exploration**: The dataset ('mushrooms.csv') is imported using Pandas, and the first 5 rows are displayed to understand its structure.

2. **Data Encoding**: Categorical data is encoded into numerical format using LabelEncoder from Scikit-learn, making it suitable for machine learning algorithms.

3. **Data Splitting**: The dataset is split into training and testing sets (80% training, 20% testing) using Scikit-learn's train_test_split function. A random state of 42 is set for reproducibility.

4. **Decision Tree Classification**: A DecisionTreeClassifier is implemented with entropy as the criterion and a maximum depth of 7. The classifier is trained on the training data and used to make predictions on the test set.

5. **Decision Tree Visualization**: The trained decision tree classifier is visualized using the plot_tree function from Scikit-learn. Column names are set to mushroom features, and class names are defined as 'edible' or 'poisonous'.

6. **Model Evaluation**: Accuracy of the classifier is calculated, and a classification report is printed, including precision, recall, and F1-score for each class. A confusion matrix is plotted using Seaborn's heatmap function to visualize the performance of the classifier.

### Usage

1. Ensure Python environment with necessary libraries (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn) is set up.
2. Clone this repository.
3. Make sure the dataset ('mushrooms.csv') is available locally or uploaded to the appropriate directory within the project repository.
4. Run the provided Python script to execute the data preprocessing, model training, and evaluation steps.



