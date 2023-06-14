Churn Modelling 

This project implements an Artificial Neural Network (ANN) to predict customer churn in a bank. The goal is to build a model that can accurately classify customers as churned or not based on various features.

Dataset

The dataset used for this project is available as a CSV file named "Churn_Modelling.csv". It includes information such as customer attributes (e.g., credit score, age, gender, geography), banking details (e.g., balance, number of products), and customer behavior (e.g., whether they have a credit card, active membership, estimated salary).

Code

The code is implemented in a Jupyter Notebook file named "Churn Modelling_ANN.ipynb". It covers the following steps:

Data Preprocessing:

Importing necessary libraries
Loading the dataset
Encoding categorical data (Label Encoding and One Hot Encoding)
Splitting the dataset into the training set and test set
Feature scaling
Building the ANN:

Initializing the ANN

Adding input and hidden layers
Adding the output layer
Training the ANN:

Compiling the ANN

Training the ANN on the training set
Making predictions and evaluating the model:

Evaluating the model on the test set

Predicting the churn status for the test set
Creating a confusion matrix to assess model performance
Predicting the result of a single observation:

Demonstrating how to use the trained ANN to predict churn for a single customer
Usage

To run the code and reproduce the results, follow these steps:

Clone the repository or download the "Churn Modelling_ANN.ipynb" file.
Open the Jupyter Notebook file in Jupyter Notebook or any compatible environment.
Ensure the required libraries are installed.
Run the code cells sequentially to execute the data preprocessing, model building, training, and evaluation steps.
The final results, including model accuracy and the confusion matrix, will be displayed in the notebook.
Feel free to explore and modify the code as needed to experiment with different parameters, architectures, or techniques.

References

Original file: Churn Modelling_ANN.ipynb

Dataset source: Churn_Modelling.csv

