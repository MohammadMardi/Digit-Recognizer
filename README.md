# Digit Recognition with Machine Learning

This project demonstrates the use of various machine learning algorithms to recognize handwritten digits using the [sklearn.datasets.load_digits](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html) dataset. We have implemented and compared the performance of three different algorithms: SVM (Support Vector Machine), ANN (Artificial Neural Network), and Random Forest.


## Introduction
This project aims to explore and compare different machine learning algorithms for the task of digit recognition. The `load_digits` dataset from `sklearn.datasets` is used for training and testing the models. Each algorithm is evaluated based on its accuracy and performance metrics.

## Dataset
The `load_digits` dataset contains 1797 samples of handwritten digits (0-9). Each sample is an 8x8 image that represents a digit.

## Algorithms
### SVM
Support Vector Machines (SVM) are powerful and versatile classifiers, capable of performing both linear and non-linear classification. In this project, we used the `SVC` class from `sklearn.svm`.

### ANN
Artificial Neural Networks (ANN) are computational models inspired by the human brain. We implemented a simple neural network using the `MLPClassifier` class from `sklearn.neural_network`.

### Random Forest
Random Forest is an ensemble learning method that operates by constructing multiple decision trees during training and outputting the class that is the mode of the classes of the individual trees. We used the `RandomForestClassifier` class from `sklearn.ensemble`.

## Results
The performance of each algorithm was evaluated using accuracy as the primary metric. Below are the accuracy scores for each algorithm:
- **Accuracy:**
- 
  ![Cancer Detection](https://github.com/MohammadMardi/DigitsDetection/blob/main/Train%20Accuracy.png)

  ![Cancer Detection](https://github.com/MohammadMardi/DigitsDetection/blob/main/Test%20Accuracy.png)


- **Precision:**
  
  ![Cancer Detection](https://github.com/MohammadMardi/DigitsDetection/blob/main/Precision.png)

- **Recall:**

  
![Cancer Detection](https://github.com/MohammadMardi/DigitsDetection/blob/main/Recall.png)
