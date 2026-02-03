Stellar Luminosity Modeling
Linear and Polynomial Regression from First Principles

Project Description
This project studies the relationship between stellar luminosity, stellar mass, and stellar temperature using linear and polynomial regression models implemented from first principles.
No machine learning libraries are used; instead, the hypothesis functions, loss functions, gradients, and optimization algorithms are explicitly defined and implemented using NumPy.

The project is part of a Machine Learning Bootcamp within a course on Digital Transformation and Enterprise Architecture, where machine learning is treated as a core architectural capability in modern cloud-based systems.

Notebooks Overview
01
Linear regression with one feature (stellar mass)
Explicit implementation of:
hypothesis function
mean squared error cost
gradients
gradient descent (non-vectorized and vectorized)
Visualization of:
dataset
cost surface
convergence behavior
Analysis of learning rates, iterations, noise, and model limitations
02
Polynomial regression with multiple engineered features
Feature set includes:
mass (M)
temperature (T)
mass squared (M²)
interaction term (M·T)
Comparison of multiple models with increasing complexity
Analysis of interaction importance
Inference example for a new star
AWS SageMaker Execution Evidence
The two notebooks were uploaded to AWS SageMaker Studio and executed successfully in a cloud environment.
All cells ran without errors, and all required plots were rendered correctly.

Notebooks visible in SageMaker Studio
alt text

Notebook 1 – Successful Execution
alt text alt text alt text alt text alt text alt text alt text alt text alt text alt text alt text

Notebook 1 – Cost Surface and Convergence Plot
Notebook 1 plot

Notebook 1 – Vectorizacion
alt text alt text alt text alt text

Notebook 2 – Polynomial Regression and Interaction Plot
alt text alt text alt text alt text alt text alt text alt text

Local vs SageMaker Execution
The notebooks were initially executed locally without issues.
Execution in AWS SageMaker produced identical numerical results and plots.

The main difference lies in the execution environment:

Local execution depends on the user's machine and setup
SageMaker provides a managed, scalable cloud environment suitable for enterprise-level machine learning workflows
How to Run Locally
Clone the repository:
Open the notebooks using Jupyter Notebook or JupyterLab
Ensure the following libraries are installed:
Python 3
NumPy
Matplotlib
Run all cells in order
Author
Diego Alejandro Rozo Gaviria

License
This project is for academic purposes only.
