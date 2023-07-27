# Decision Tree Base Model for Iris, Wine, and Boston Datasets

This repository contains Python code that demonstrates how to implement a decision tree base model to predict on the Iris, Wine, and Boston datasets using scikit-learn.

## Prerequisites

Before running the code, make sure you have the following installed:

- Python (>= 3.6)
- scikit-learn (>= 0.24)

You can install the required packages using the following command:

```bash
pip install scikit-learn
```

## Dataset Information

### Iris Dataset

The Iris dataset is a classic dataset for classification tasks. It contains 150 samples of iris flowers, with four features (sepal length, sepal width, petal length, petal width) and three classes (Setosa, Versicolor, and Virginica).

### Wine Dataset

The Wine dataset contains 178 samples of different wines, with 13 features that describe various chemical properties. The dataset is divided into three classes (wine cultivars).

### Boston Housing Dataset

The Boston Housing dataset contains information about houses in Boston and their corresponding median values. It consists of 506 samples, with 13 features related to the houses and the target variable being the median value of owner-occupied homes.

## How to Use

1. Clone the repository to your local machine:

```bash
git clone https://github.com/SGGODE/Decision_Tree_RC.git
```
2. Navigate to the project directory:
```
cd project_dir
```
3. Run the Python script for the Iris dataset:
```
python iris_decision_tree.py
```
4. Run the Python script for the Wine dataset:
```
python wine_decision_tree.py
```
5. Run the Python script for the Boston dataset:
```
python boston_decision_tree.py
```
The decision tree models will be trained and evaluated on the respective datasets. The results, including accuracy (for classification tasks) and mean squared error (for regression tasks), will be displayed on the console.
