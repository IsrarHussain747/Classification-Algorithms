Binary Classification of Iris Dataset

Project Overview

This project implements binary classification on a modified Iris dataset using three machine learning models:

Logistic Regression

Decision Tree Classifier

K-Nearest Neighbors (KNN) Classifier

The goal is to classify iris flowers into two categories based on their features and compare model performances.

Dataset

The dataset contains multiple features representing iris flowers, with the last column as the target class (Class 0 or Class 1). The data is split into training (80%) and testing (20%) sets.

Technologies Used

Python

Scikit-learn

Pandas

NumPy

Matplotlib

Seaborn

Installation

To run this project, ensure you have Python installed, then install the necessary libraries:

pip install pandas numpy scikit-learn matplotlib seaborn

Project Structure

│── binary_iris_dataset.csv   # Dataset file
│── main.py                   # Main script for training and evaluation
│── README.md                 # Project documentation

Usage

Run the script to train and evaluate the models:

python main.py

Model Evaluation

Each model's performance is assessed using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-squared Score (R²)

Confusion Matrix (Visualized using Seaborn)

Results

Logistic Regression provides stable performance.

Decision Tree may overfit.

KNN performance depends on the choice of n_neighbors.
