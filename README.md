# ml-lab-2
Logistic Regression with Gradient Ascent

This project implements binary logistic regression from scratch, without ML libraries, for CSCI 4465 (Machine Learning). It generates a synthetic dataset of 200 examples with two features, split evenly between two Gaussian-distributed classes. It then estimates the parameter vector θ by maximizing the log-likelihood with gradient ascent, stopping once the change in log-likelihood between iterations falls below 10⁻³. The final output is a plot of the dataset with the learned decision boundary separating the two classes.

Tech: Python, NumPy, Matplotlib

Run: python main.py
