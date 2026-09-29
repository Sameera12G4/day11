# Iris Classification Using Neural Network

## Objective

The objective of this project is to build a basic Neural Network Classification model using TensorFlow and Keras to classify Iris flowers into different species.

## Dataset

The Iris dataset contains:

- 150 samples
- 4 input features
- 3 classes

The three flower classes are:

- Setosa
- Versicolor
- Virginica

The four features are:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset is loaded using Scikit-learn.

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the Iris dataset.
2. Separated features and target values.
3. Split the dataset into training and testing data.
4. Used `StandardScaler` to standardize the features.

The data was divided into:

- 80% Training data
- 20% Testing data

## Neural Network Architecture

The neural network contains:

```text
Input Layer
     ↓
Dense Layer - 16 neurons - ReLU
     ↓
Dense Layer - 8 neurons - ReLU
     ↓
Output Layer - 3 neurons - Softmax