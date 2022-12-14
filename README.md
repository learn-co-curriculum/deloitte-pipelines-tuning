# Overview of Pipelines with Model Tuning

## Introduction

Now that you have learned about both supervised and unspervised learning workflows, it's time to get into some more advanced techniques. In this section you'll learn about tools for tuning model hyperparameters and building pipelines.

## Tuning Model Hyperparameters with GridSearchCV

With non-parametric models such as decision trees, you have seen that there are various hyperparameters that you can specify when you instantiate the model. For example, the maximum depth of the tree. Often these hyperparameters help to balance the bias-variance trade-off between underfitting and overfitting and are important for finding the optimal model.

With so many different hyperparameter combinations to try out, it can be difficult to write clean, readable code. Fortunately there is a tool from scikit-learn called `GridSearchCV` that is specifically designed to search through a "grid" of hyperparameters! In this section we'll introduce how to use this tool.


## Machine Learning Pipelines

Pipelines are extremely useful for allowing data scientists to quickly and consistently transform data, train machine learning models, and make predictions.

By now, you know that the data science process is a flow of activities, from inspecting the data to cleaning it, transforming it, running a model, and discussing the results. Wouldn't it be nice if there was a streamlined process to create nice machine learning workflows? Enter the `Pipeline` class in scikit-learn!

In this section, you'll learn how you can use a pipeline to integrate several steps of the machine learning workflow by learning an extension of decision trees called random forests. Additionally, you'll compare several classification techniques with each other, and integrate grid search in your pipeline so you can tune several hyperparameters in each of the machine learning models while also avoiding data leakage.


## Summary

This section only scratches the surface of the advanced modeling tools you might use as a data scientist. Get ready to optimize your workflow and get beyond the basics!
