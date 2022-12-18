# Credit Card Fraud Detection - SVM's


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Support Vector Machines, or SVMs for short, is a type of machine learning algorithm that is used to classify things. Imagine you have a bunch of points on a graph, and you want to know how to draw a line that separates the points into different groups. SVMs can help you find that line!

Here's how it works: First, you need to choose a line that separates the points into different groups as best as possible. This line is called the "decision boundary." Then, you need to find the points that are closest to the decision boundary. These points are called "support vectors." The line that goes through the support vectors is the final decision boundary.

SVMs are useful because they can help you classify things accurately. For example, if you have a bunch of data about different types of flowers, you can use an SVM to classify the flowers into different groups based on their characteristics.

## Uses

- Classification: SVMs can be used to classify data into different categories. For example, they can be used to classify emails as spam or not spam, or to classify images as containing certain objects or not.
- Regression: SVMs can also be used for regression tasks, where the goal is to predict a continuous output value.
- Anomaly detection: SVMs can be used to identify unusual patterns or observations in a dataset. This can be useful for detecting fraud or other unusual activity.
- Feature selection: SVMs can be used to identify the most important features in a dataset, which can be useful for building predictive models.


## Steps to implement Credit Card Fraud Detection

- Start by collecting and preparing your data. You'll need a dataset of credit card transactions, along with labels indicating whether each transaction was fraudulent or not. You'll also need to split the data into training and test sets.

- Preprocess the data. This may include cleaning and normalizing the data, as well as handling missing values and outliers.

- Choose an appropriate kernel for the SVM. If the data is linearly separable, you can use a linear kernel. If the data is not linearly separable, you may need to use a non-linear kernel such as the radial basis function (RBF) kernel.

- Train the SVM model on the training data. This will involve fitting the model to the data and selecting the best parameters for the kernel and other hyperparameters.

- Evaluate the model on the test data. This will involve making predictions on the test data and evaluating the model's performance using metrics such as accuracy, precision, and recall.

- Fine-tune the model if necessary. If the model's performance is not satisfactory, you may need to adjust the hyperparameters or try a different kernel.

![Alt text](https://html.scirp.org/file/4-7404597x20.png "a title")


## References
- https://machinelearningmastery.com/support-vector-machines-for-machine-learning/
- https://towardsdatascience.com/support-vector-machines-a-simple-explanation-f6d1cd86b0a1
- https://www.youtube.com/watch?v=U9-ZsbaaGAs   
