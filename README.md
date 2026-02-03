# Workshop – Linear Regression and Vectorization
##Author
- Diego Alejandro Rozo Gaviria
  
## 1. General Information

- **Course:** Digital Transformation and Enterprise Architecture  
- **Topic:** Linear Regression from Scratch and Vectorization  
- **Student:** Diego Alejandro Rozo  
- **Academic Period:** 2026-1  

---

## 2. Workshop Objective

The objective of this workshop is to understand the fundamentals of **linear regression** by implementing it from scratch, both in its **non-vectorized** and **vectorized** versions. The workshop analyzes the impact of different hyperparameters such as the learning rate, number of iterations, and noise level in the data.

Additionally, the workshop aims to reinforce the use of **vectorization** to improve computational efficiency and code clarity.

---

## 3. Repository Structure

<img width="345" height="188" alt="image" src="https://github.com/user-attachments/assets/c5d52958-ebed-4dfd-af28-ddcda6eda304" />

---

## 4. Notebook Description

### 4.1 Non-Vectorized Linear Regression

This notebook implements linear regression using explicit loops (`for`), covering:

- Hypothesis function
- Cost function
- Manual gradient computation
- Gradient descent
- Model fitting visualization

This approach allows a step-by-step understanding of the mathematical behavior of the algorithm.

---

### 4.2 Vectorized Linear Regression

This notebook implements the same linear regression using **NumPy vectorized operations**, which allows:

- Reduced code complexity
- Improved computational performance
- Easier scalability to larger datasets

The numerical results obtained are equivalent to those of the non-vectorized model.

---

## 5. Execution in AWS SageMaker

The notebooks were uploaded and executed successfully in **AWS SageMaker Studio**, verifying correct functionality in a cloud-based environment.

### Execution evidence:


<img width="474" height="1032" alt="image" src="https://github.com/user-attachments/assets/d03c20c9-5a43-4cd2-885f-e780e4cbfae2" />
<img width="1881" height="756" alt="image-1" src="https://github.com/user-attachments/assets/7f1eb86d-bf62-4996-ba00-6a50095dfa39" />
<img width="1148" height="532" alt="image-2" src="https://github.com/user-attachments/assets/77ffc3ab-6229-4c2c-bed2-bee708c467e4" />
<img width="1919" height="1016" alt="image-3" src="https://github.com/user-attachments/assets/7a5911d7-9b7d-4c94-8fcf-7f16dd581b76" />
<img width="1919" height="978" alt="image-4" src="https://github.com/user-attachments/assets/7f9d1290-923a-4617-94a5-e4edd2fe3deb" />
<img width="1919" height="1017" alt="image-5" src="https://github.com/user-attachments/assets/a4dcb5d0-c1ec-43b3-aaba-bb1451e6fa42" />
<img width="1919" height="1022" alt="image-6" src="https://github.com/user-attachments/assets/e0a7c52b-06fb-405e-8e1c-50a5c58fd438" />
<img width="1919" height="1008" alt="image-7" src="https://github.com/user-attachments/assets/5358d82a-6c70-4a44-8145-8447a7452eb0" />
<img width="1919" height="1014" alt="image-8" src="https://github.com/user-attachments/assets/4860ca33-49b4-45fe-8733-305f003bb1d9" />
<img width="1391" height="994" alt="image-9" src="https://github.com/user-attachments/assets/47678c68-a8b0-4410-b25d-039ea59cd825" />
<img width="1491" height="744" alt="image-10" src="https://github.com/user-attachments/assets/3c335d93-9bc6-4afa-adae-72cf54d7d10e" />
<img width="1919" height="1014" alt="image-11" src="https://github.com/user-attachments/assets/767684ed-38d3-40fb-83f8-9cf94e1140aa" />
<img width="1918" height="1002" alt="image-12" src="https://github.com/user-attachments/assets/238a3771-504c-4d69-94a2-28631bdd277a" />
<img width="1919" height="991" alt="image-13" src="https://github.com/user-attachments/assets/58f724f1-4dda-4d0b-bc2d-8d02cbcfd1fd" />
<img width="1918" height="1013" alt="image-14" src="https://github.com/user-attachments/assets/099607d8-1929-4084-8946-6bab8ca177c7" />
<img width="1919" height="1024" alt="image-15" src="https://github.com/user-attachments/assets/c72f9d38-8da4-46cb-bb6d-3cbb8788ff72" />
<img width="1919" height="1018" alt="image-16" src="https://github.com/user-attachments/assets/cd7c3816-c480-4b1a-ad18-854fbbe1609d" />
<img width="1919" height="1022" alt="image-17" src="https://github.com/user-attachments/assets/26503eff-79d9-4420-bf52-1a29007166d0" />
<img width="1919" height="1029" alt="image-19" src="https://github.com/user-attachments/assets/035ff4cc-dbe4-44b9-bd33-a446ef3d24ff" />
<img width="1919" height="1022" alt="image-20" src="https://github.com/user-attachments/assets/f79d202f-1c71-4cdf-b7a7-7af28141d78d" />
<img width="1918" height="1023" alt="image-21" src="https://github.com/user-attachments/assets/ea496561-5bdb-424d-8e9a-6dade0bc25b8" />
<img width="1919" height="1022" alt="image-22" src="https://github.com/user-attachments/assets/652cd0f1-bbfd-4175-b92d-fbc98af1acec" />






---

## 6. Results and Analysis

- Increasing the learning rate accelerates convergence, but excessively large values cause divergence.
- Increasing the number of iterations reduces the final cost until convergence stabilizes.
- Vectorization does not change the mathematical results, but significantly improves efficiency.
- Higher noise levels in the data reduce the accuracy of the fitted model.

---

## 7. Conclusions

- Linear regression can be fully implemented from scratch without high-level ML libraries.
- Vectorization is a key technique for writing efficient and readable numerical code.
- AWS SageMaker provides a reliable environment for executing machine learning notebooks.
- Understanding the non-vectorized implementation facilitates comprehension of the vectorized approach.

---

## 8. Requirements

- Python 3.x  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 9. Notes

This workshop is for academic purposes and is part of the learning process of Machine Learning fundamentals.



