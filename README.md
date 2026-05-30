# Iris Flower Classification using K-Nearest Neighbors (KNN)

## Project Overview

This project demonstrates the fundamentals of supervised machine learning by building a classification model using the Iris dataset. The model is trained to predict the species of an iris flower based on its physical measurements.

The project covers the complete machine learning workflow, including data loading, preprocessing, train-test splitting, model training, prediction, and evaluation.

---

## Objective

The goal of this project is to:

* Load and understand a dataset
* Split data into training and testing sets
* Train a classification model
* Evaluate model performance
* Learn the basics of supervised learning

---

## Dataset

The project uses the Iris dataset, a well-known dataset in machine learning.

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target Classes

* Setosa
* Versicolor
* Virginica

The dataset contains 150 samples equally distributed among the three flower species.

---

## Technologies Used

* Python 3
* Scikit-learn

---

## Machine Learning Algorithm

### K-Nearest Neighbors (KNN)

KNN is a simple supervised learning algorithm that classifies a new data point based on the majority class of its nearest neighbors.

In this project:

* Number of neighbors (K) = 3
* Classification Type = Multi-class Classification

---

## Project Workflow

### 1. Load Dataset

Load the Iris dataset from Scikit-learn.

### 2. Prepare Features and Labels

* Features (X): Flower measurements
* Labels (y): Flower species

### 3. Split Dataset

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

### 4. Train Model

The KNN classifier is trained using the training data.

### 5. Make Predictions

The trained model predicts the species of flowers in the testing dataset.

### 6. Evaluate Performance

Model accuracy is calculated using the Accuracy Score metric.

---

## Installation

Install the required package:

```bash
pip install scikit-learn
```

---

## Running the Project

Execute the Python file:

```bash
python iris_classifier.py
```

---

## Sample Output

```text
Accuracy: 0.9666666666666667
```

The accuracy may vary slightly depending on the train-test split.

---

## Skills Demonstrated

* Data Handling
* Dataset Exploration
* Supervised Learning
* Classification
* Model Training
* Model Evaluation
* Machine Learning Fundamentals

---

## Learning Outcomes

By completing this project, you will understand:

* How machine learning datasets are structured
* The difference between training and testing data
* How classification algorithms work
* How to train and evaluate a machine learning model
* The complete workflow of a simple ML project

---

## Future Improvements

Possible enhancements include:

* Testing additional classification algorithms
* Hyperparameter tuning
* Data visualization
* Cross-validation
* Performance comparison using multiple models
* Deploying the model as a web application

---

## Author

Developed as a beginner machine learning project to demonstrate the fundamentals of classification and supervised learning using Python and Scikit-learn.
