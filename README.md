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

## Usage with scikit-learn Built-in Datasets
In the Python scripts (iris_decision_tree.py, wine_decision_tree.py, and boston_decision_tree.py), the datasets are loaded using scikit-learn's built-in datasets. This makes it easier to use the datasets without downloading them separately.

Here's an example of how to load the Iris dataset in the iris_decision_tree.py script:
```
from sklearn.datasets import load_iris

# Load the Iris dataset
iris = load_iris()
X = iris.data
y = iris.target
```
Similarly, you can load the Wine dataset in the wine_decision_tree.py script:
```
from sklearn.datasets import load_wine

# Load the Wine dataset
wine = load_wine()
X = wine.data
y = wine.target
```
And load the Boston dataset in the boston_decision_tree.py script:
```
from sklearn.datasets import load_boston

# Load the Boston dataset
boston = load_boston()
X = boston.data
y = boston.target
```
The rest of the code in each script demonstrates how to train and evaluate a decision tree model on the respective dataset using scikit-learn's DecisionTreeClassifier for classification tasks and DecisionTreeRegressor for regression tasks.
