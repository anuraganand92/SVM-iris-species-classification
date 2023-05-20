## Species Classification on Iris Dataset using Support Vector Machine (SVM)

### Project Description

This project focuses on species classification using **Support Vector Machine (SVM)** on the **Iris dataset**. The Iris dataset is a widely used benchmark dataset in **machine learning**. The goal is to **train an SVM model with different kernels** and **evaluate its performance using test classification accuracy**. The project also includes visualizing the **performance of the SVM model for each kernel** and **conducting a comparative analysis for different values of gamma in the RBF kernel**.

### Dataset

The Iris dataset is available at the following link: [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris). It contains measurements of four features (sepal length, sepal width, petal length, and petal width) for three different species of Iris flowers (*setosa*, *versicolor*, and *virginica*). The dataset consists of 150 samples, with 50 samples for each species.

### Project Steps

1. **Data Split**: Split the Iris dataset into a training set and a test set with a ratio of 8:2. The training set will be used to train the SVM model, while the test set will be used to evaluate the model's performance.

2. **SVM with Different Kernels**: Train and test the SVM model with four different kernels:
    - Linear kernel
    - Polynomial kernel with degree 3
    - RBF kernel with gamma = 0.5
    - Sigmoid kernel

3. **Test Accuracy Evaluation**: Compute the test classification accuracy for each SVM model using the different kernels.

4. **Performance Visualization**: Visualize the performance of the SVM models by plotting the test accuracy for each kernel. This visualization will provide insights into the relative performance of the different kernels.

5. **Comparative Analysis for RBF Kernel**: Focus on the RBF kernel and perform a comparative analysis by training and testing the SVM model with different values of gamma (0.3, 0.5, 0.7, 0.9). Visualize the comparative analysis to observe the impact of gamma on the model's performance.
