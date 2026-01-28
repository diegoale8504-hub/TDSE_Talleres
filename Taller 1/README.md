# Stellar Luminosity Modeling  
Linear and Polynomial Regression from First Principles

## Project Description

This project studies the relationship between stellar luminosity, stellar mass, and stellar temperature using linear and polynomial regression models implemented from first principles.  
No machine learning libraries are used; instead, the hypothesis functions, loss functions, gradients, and optimization algorithms are explicitly defined and implemented using NumPy.

The project is part of a Machine Learning Bootcamp within a course on Digital Transformation and Enterprise Architecture, where machine learning is treated as a core architectural capability in modern cloud-based systems.

---


---

## Notebooks Overview

### 01
- Linear regression with **one feature (stellar mass)**  
- Explicit implementation of:
  - hypothesis function
  - mean squared error cost
  - gradients
  - gradient descent (non-vectorized and vectorized)
- Visualization of:
  - dataset
  - cost surface
  - convergence behavior
- Analysis of learning rates, iterations, noise, and model limitations

### 02  
- Polynomial regression with **multiple engineered features**
- Feature set includes:
  - mass (M)
  - temperature (T)
  - mass squared (M²)
  - interaction term (M·T)
- Comparison of multiple models with increasing complexity
- Analysis of interaction importance
- Inference example for a new star

---

## AWS SageMaker Execution Evidence

The two notebooks were uploaded to **AWS SageMaker Studio** and executed successfully in a cloud environment.  
All cells ran without errors, and all required plots were rendered correctly.

### Notebooks visible in SageMaker Studio
![alt text](image.png)

### Notebook 1 – Successful Execution
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-7.png)
![alt text](image-8.png)
![alt text](image-9.png)
![alt text](image-10.png)
![alt text](image-11.png)
### Notebook 1 – Cost Surface and Convergence Plot
![Notebook 1 plot](images/notebook1_plot.png)

### Notebook 1 – Vectorizacion
![alt text](image-12.png)
![alt text](image-13.png)
![alt text](image-14.png)
![alt text](image-15.png)
### Notebook 2 – Polynomial Regression and Interaction Plot
![alt text](image-16.png)
![alt text](image-17.png)
![alt text](image-18.png)
![alt text](image-19.png)
![alt text](image-20.png)
![alt text](image-21.png)
![alt text](image-22.png)
## Local vs SageMaker Execution

The notebooks were initially executed locally without issues.  
Execution in AWS SageMaker produced **identical numerical results and plots**.

The main difference lies in the execution environment:
- Local execution depends on the user's machine and setup
- SageMaker provides a **managed, scalable cloud environment** suitable for enterprise-level machine learning workflows

---

## How to Run Locally

1. Clone the repository:
2. Open the notebooks using Jupyter Notebook or JupyterLab
3. Ensure the following libraries are installed:
- Python 3
- NumPy
- Matplotlib
4. Run all cells in order

---

## Author

**Diego Alejandro Rozo Gaviria**

---

## License

This project is for academic purposes only.
