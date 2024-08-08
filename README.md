# Implementing Linear Regression From Scratch Using Python

This repository contains a Python implementation of Linear Regression from scratch, using only basic libraries like NumPy and pandas. The project demonstrates how to build and train a Linear Regression model, perform predictions, and visualize the results.

## Project Overview

Linear Regression is a fundamental machine learning algorithm used to predict a continuous target variable based on one or more features. This project involves creating a Linear Regression model, training it with a dataset, and making predictions.

## Project Structure

1. **`Linear_Regression` class**: Implements the core functionality of the Linear Regression model, including training using gradient descent and making predictions.
2. **Data Pre-Processing**: Loads and prepares the data from a CSV file.
3. **Model Training**: Trains the Linear Regression model using the processed data.
4. **Visualization**: Plots the predicted values against the actual values.

## How Did I Do It?

Here’s a breakdown of the implementation:

### Linear Regression Implementation

- **Class Definition**: Defined a `Linear_Regression` class with methods for initialization, training (`fit`), weight updates (`update_weights`), and prediction (`predict`).
- **Gradient Descent**: Implemented gradient descent to minimize the loss function. This involved calculating gradients for weights and bias and updating them iteratively.
- **Prediction**: Used the learned weights and bias to predict salary values for new data points.

### Data Pre-Processing and Model Training

- **Loading Data**: Read the dataset from a CSV file using pandas and performed initial exploration (e.g., checking for missing values, viewing data samples).
- **Splitting Data**: Split the data into training and test sets using `train_test_split` from scikit-learn.
- **Training the Model**: Created an instance of the `Linear_Regression` class, configured with a learning rate and number of iterations, and fitted it to the training data.

### Visualization

- **Plotting Results**: Visualized the model’s predictions compared to actual values using Matplotlib to assess the model's performance visually.

## Impact
This project enhanced my understanding of Linear Regression, gradient descent, and practical implementation challenges. It served as a solid foundation for more advanced machine learning projects.
