# Credit Card Fraud Analysis

<p align="center">
  <img src="detective.png" >
</p>

Hello, everybody!

I made this notebook to exercise some different classification models that I've been studying on the previous weeks. I didn't develop the optimization of these models nor the tuning, hyper-parameters and etc.

It's more about having an idea of how the models work with different performances in the same dataset. It's good to have an experience about which models has a greater likelihood to perform well depending on the situation.

By the way, was a nice opportunity to figure out how to work with an imbalanced dataset. As the theme is related to detect credit card fraud, it's better to care more about the minority dataset, which is what we're trying to cat. Due to this strategy, I chose to work with an undersampling approach.

Here's a summary about the theoretical part of what I explored in the notebook. I hope you like it and, if so, please consider to leave a star for me =)

Your feedback is really welcome!

## Logistic Regression

Logistic Regression is an ML classification algorithm that uses one or more independent variables to determine the outcome.

The goal of Logistic Regression is to determine the best relationship between the features and the dependent variable, the target. It is better than other binary classification algorithms because it quantitatively explains the factors leading to the classification.

## Advantages and Disadvantages

Logistic regression is aimed at classifications, especially in understanding how the features affect the dependent variable.

The main disadvantage of this algorithm is its focus on predicting binary variables, as well as assuming no missing values and that the predictors are independent.

It is used for:

- Identifying risk factors for diseases
- Word classification
- Weather forecasting
- Elections

## Naive Bayes Classifier

It is a classification based on Bayes' theorem, which assumes independence between the features.

Even if the features depend on each other, all these properties contribute to the probability independently. This model is easy to build and particularly useful for large databases.

## Advantages and Disadvantages

It requires a small amount of training data to estimate the necessary parameters and is very fast compared to other classifiers.

The disadvantage is the fact that they are known as poor estimators.

It is used for:

- Disease prediction
- Document classification
- Spam filters
- Sentiment analysis

## K-Nearest Neighbor

It is a lazy learning algorithm that stores all instances corresponding to training data in an n-dimensional space. Its focus is on storing training instances rather than building a general model.

Classification is computed from the label of the majority of a number k of the closest neighbors of a given data point.

## Advantages and Disadvantages

The algorithm is relatively simple to implement and is robust against noise from the training dataset. Even if the dataset is large, it is very efficient.

The only disadvantage is not having control over the k value, and the computational cost is relatively high compared to other algorithms.

It is used for:

- Industrial applications
- Handwriting detection
- Image and video recognition
- Stock analysis

## Decision Tree

A decision tree builds the classification model in a tree format. It uses if-then rules along the branches.

The process follows the branches of a tree into increasingly smaller structures. The final structure looks like an upside-down tree.

The rules are learned sequentially using the training dataset. The process continues until the tree reaches a termination point.

The tree is built by recursive splitting, with a node being the split (or branching) if-else point.

The interesting thing about a decision tree is its application to both numerical and categorical data.

## Advantages and Disadvantages

The advantages include simplicity of understanding and visualization, and requiring little data preparation.

The disadvantage is it can become very complex. This can be somewhat unstable as changes in data can radically alter the structure of the decision tree.

It is used for:

- Data exploration
- Pattern recognition
- Pricing
- Disease and threat/risk identification


Source:
https://www.edureka.co/blog/classification-in-machine-learning/
