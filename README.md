# Machine-Learning-Methods_vs_Deep-Learning-Model
**Comparing Different Machine Learning Methods to Deep Learning Models and how to use each models based on their datas.**

## Overview

## Logistic Regression Model vs Basic Neural Network 

**A logistic regression model is a classification algorithm that can analyze continuous and categorical variables. Using a combination of input variables, logistic regression predicts the probability of the input data belonging to one of two groups. Also statistical model that mathematically determines its probability of belonging to one of two groups.**

**In Basic Neural Network the sigmoid curve is the exact same curve used in the sigmoid activation function of a neural network.**


- **In the [LogisticRegression_NeuralNet](LogisticRegression_NeuralNet.ipynb) file we demonstrate how similar the logistic regression and basic neural network models are in terms of performance, we'll also build and evaluate both models using the same training/testing dataset using the ***Diabetes Dataset.*****

#### Results 

- **we compare both model's predictive accuracy, their output is very similar. Either model was able to predict whether or not a patient is diagnosed with diabetes more than 70% of the time.** 

#### **Possible reasons that both models could not achieve 80% predictive accuracy?**

- **The input data was insufficient—there were not enough data points and too few features.**

- **Both models are lacking optimization (parameters, structure, and weights).** 

- **There are features in the input data that confuse the model.** 

##  Support Vector Machine vs. Deep Learning Model

**SVMs(Support Vector Machine) are supervised learning models that analyze data used for regression and classification. SVMs are a type of binary classifier that use geometric boundaries to distinguish data points from two separate groups. More specifically, SVMs try to calculate a geometric hyperplane that maximizes the distance between the closest data point of both groups.SVMs can build adequate models with linear or nonlinear data. Due to SVMs' ability to create multidimensional borders. SVMs lose their interpretability and behave more like the black box machine learning models, such as basic neural networks and deep learning models.** 

**Comparisons**

**SVMs have an advantage over neural network and deep learning models:**

- **Neural networks and deep learning models will often converge on a local minimum. In other words, these models will often focus on a specific trend in the data and could miss the "bigger picture."**

- **SVMs are less prone to overfitting because they are trying to maximize the distance, rather than encompass all data within a boundary.
Despite these advantages, SVMs are limited in their potential and can still miss critical features and high-dimensionality relationships that a well-trained deep learning model could find.** 

**In the [SVM_DeepLearning](SVM_DeepLearning.ipynb) we compare and contrast the performance of an SVM versus Deep Learning Model using the ***Bank Telemarketing Dataset.*****

#### Results 

**Comparing the analysis of both results, the SVM and deep learning models both achieved a predictive accuracy around 87%. The only noticeable difference between the two models is implementation—the amount of code required to build and train the SVM is notably less than the comparable deep learning model.** 










## Resources 

- [Diabetes Dataset](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_19/diabetes.csv) 

- [Bank Telemarketing Dataset](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_19/bank_telemarketing.csv) 

- 

