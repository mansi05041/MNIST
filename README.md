# MNIST Hands On
The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems.

## Table of contents
- [Overview](#overview)
- [Methodology](#methodology)
- [Jupyter Files](#links)
- [Result](#result)
- [Useful resources](#useful-resources)
- [Contributors](#contributors)

## Overview
<strong>Performing various machine learning models on the MNIST dataset</strong> 

### Methodology
- Data Collection
- Data Preprocessing
- Feature Engineering
- Model Training & Evaluation

### Links
Models Implemented:
- [ANN](https://github.com/mansi05041/MNIST/blob/main/MNIST_ANN.ipynb)
- [Decision Tree](https://github.com/mansi05041/MNIST/blob/main/MNIST_DecisionTree.ipynb)
- [KNN](https://github.com/mansi05041/MNIST/blob/main/MNIST_KNN.ipynb)
- [Naive Bayes](https://github.com/mansi05041/MNIST/blob/main/MNIST_NaiveBayes.ipynb)
- [Random Forest](https://github.com/mansi05041/MNIST/blob/main/MNIST_RandomForest.ipynb)
- [SVM](https://github.com/mansi05041/MNIST/blob/main/MNIST_SVM.ipynb)

### Result
Accuracy </br>
- <strong>ANN</strong>:0.9781
- <strong>DT</strong>:0.8755
- <strong>KNN</strong>:0.9705
- <strong>NB</strong>:0.554
- <strong>RF</strong>:0.9704
- <strong>SVM</strong>:0.9417

### Conclusions
- ANN achieves the highest accuracy indicating its effectiveness in capturing complex patterns within the dataset.
- KNN gets high accuracy indicating its effectiveness in classfying data points based on their similarity to the neighbouring points.
- RF also performs well demonstrating its ability to handle high-dimensional data and capture interactions between features.
- SVM achieves accuracy which is slightly lower to the top performing models but still demonstrates its capability in handling complex classification tasks.
- DT accuracy is lower compared to the other models, suggesting that it may not capture the complexity of the MNIST dataset as effectively.
- NB achieves the lowest, indicating that its assumption of feature independence may not hold well for the MNIST dataset, which contains correlated pixel values.

### Future Work
- Model optimization by hyperparameter tuning techniques.
- Experiment with different feature extraction techniques.
- Investigate ensemble methods to improve the overall accuracy and generalization performance.

## Contributors
- [Mansi joshi](https://github.com/mansi05041)


