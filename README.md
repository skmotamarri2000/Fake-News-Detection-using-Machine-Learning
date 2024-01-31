﻿# Fake-News-Detection-using-Machine-Learning

 # Introduction
In this code, I have implemented and compared the parallel and serial execution of two popular machine learning algorithms: K-Nearest Neighbors (KNN) and Random Forest. I used the Python programming language and the scikit-learn library for this purpose.

# Parallel vs Serial Execution

The code measures the execution time of both the serial and parallel implementations of the KNN and Random Forest algorithms. It also calculates the accuracy of the models and generates classification reports and confusion matrices.

# Libraries Used for Parallel Execution

The parallel execution of the machine learning algorithms is achieved using the joblib library. The joblib library provides tools for parallel computing in Python, including parallel for loops and parallel execution of functions. It allows us to distribute the workload across multiple cores or processors, resulting in faster execution times.
In this project, the Parallel and delayed functions from the joblib library are used to parallelize the training and prediction processes. The Parallel function distributes the workload across multiple cores or processors, and the delayed function is used to delay the execution of the train_rf function until all the data is ready.
Overall, the parallel execution of machine learning algorithms can significantly reduce the execution time, especially when dealing with large datasets. It allows us to take advantage of the computational power of modern processors and achieve faster results.
