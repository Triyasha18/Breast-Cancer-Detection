# Breast-Cancer-Detection
## Objective:
The objective of this assessment is to evaluate your understanding and ability to apply supervised learning techniques to a real-world dataset.
### 1.Logistic Regression:
#### How it works: 
Logistic Regression is a linear model used for binary classification. It estimates the probability that a given input belongs to a particular class using the logistic function.
##### Suitability: 
Although the Iris dataset has three classes, Logistic Regression can be extended to multiclass classification using techniques like one-vs-rest. It's simple and effective for linearly separable data.
### 2.Decision Tree Classifier:
#### How it works: 
Decision Trees split the data into subsets based on the value of input features. Each node represents a feature, each branch represents a decision rule, and each leaf represents an outcome.
#### Suitability: 
Decision Trees are easy to interpret and can handle both numerical and categorical data. They are well-suited for the Iris dataset as they can capture complex relationships between features.
### 3.Random Forest Classifier:
#### How it works: 
Random Forest is an ensemble method that builds multiple decision trees and merges them to get a more accurate and stable prediction. It reduces overfitting by averaging the results of many trees.
#### Suitability: 
Random Forest is robust to noise and can handle large datasets with higher dimensionality. It performs well on the Iris dataset by improving the accuracy and reducing overfitting compared to a single decision tree.
### 4.Support Vector Machine (SVM):
#### How it works:
SVM finds the hyperplane that best separates the data into different classes. It maximizes the margin between the closest points of different classes (support vectors).
#### Suitability: 
SVM is effective in high-dimensional spaces and works well for both linear and non-linear classification using kernel functions. It's suitable for the Iris dataset as it can handle the overlapping classes effectively.
### k-Nearest Neighbors (k-NN):
#### How it works:
k-NN is a non-parametric algorithm that classifies a data point based on the majority class of its k nearest neighbors. It uses distance metrics like Euclidean distance to find the nearest neighbors.
#### Suitability: 
k-NN is simple and intuitive, making it a good choice for small datasets like Iris. It can capture the local structure of the data and is effective when the decision boundary is irregular.
## Summary:
We explored various machine learning techniques on the Iris dataset, starting with data preprocessing by dropping the species column. We applied KMeans and Hierarchical clustering to visualize the data structure. Additionally, we discussed five classification algorithms: Logistic Regression, Decision Tree, Random Forest, SVM, and k-NN, highlighting their mechanisms and suitability for the dataset. Each algorithm offers unique strengths, making them suitable for different aspects of the Iris dataset depending on specific requirements. 
