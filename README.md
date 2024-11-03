# SVM-from-scratch
Implementation of SVM using numpy and scipy

## Motivation
This project was created to deepen my understanding of the mathematical foundations behind SVMs. By building an SVM from scratch, I explored the fundamental concepts of margin maximization, kernel functions, and cross-validation without relying on high-level libraries like scikit-learn.
## Dataset
The model is evaluated on the classic Iris dataset, which consists of three classes of iris flowers, providing an intuitive test for multiclass classification.
## Results
The model successfully classifies all three classes in the Iris dataset with high accuracy. Visualization of decision boundaries demonstrates the effectiveness of the custom SVM implementation.
## Implementation
The project implements a Soft-Margin Kernel SVM with the following features:
* **`Kernel Options:`** The user can choose between a linear or Gaussian (RBF) kernel.
* **`Multiclass Support:`** Since the SVM is a binary classifier by nature, multiclass classification is achieved using a one-vs-all (OvA) strategy.
* **`Custom Cross-Validation:`** Implemented to evaluate the SVM's performance and ensure model robustness.
## Installation
The jupyter notebook requires the installation of standard machine learning libraries.
## Usage
The SVM model can be adapted to various datasets. However, due to the O(n²) time complexity of the algorithm, it’s challenging to scale this implementation to very large datasets. This limitation arises from the high computational cost of the kernel matrix.
## Future work
* **`Performance Optimization:`** Explore faster optimization algorithms to improve training speed.
* **`Additional Kernels:`** Implement other kernel functions, such as polynomial or sigmoid, for greater flexibility in non-linear classification.
* **`Scalability:`** Investigate approximate SVM algorithms to scale the model for larger datasets.
