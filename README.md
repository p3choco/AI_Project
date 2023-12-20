# Introduction to Artificial Intelligence: Project
This project was undertaken for the "Introduction to Artificial Intelligence" classes at my university.


## Purpose of the Project 
The objective of this project was to predict the popularity of a game based on the type of gameplay and related data.

## Project Overview

### Data Preprocessing
- Processed the initial dataset by:
  - Removing missing values
  - Dropping unnecessary data points
  - Encoding relevant features for modeling

### Model Selection
- Evaluated the efficacy of the following models for this dataset:
  - SVM with RBF kernel
  - SVM with Linear kernel
  - SVM with Polynomial kernel
  - Logistic Regression
  - Neural Network

### Parameter Tuning
- Employed GridSearch to determine the optimal parameters for the aforementioned models.

### Performance Evaluation
- Assessed the performance and reliability of each model using various metrics.

## Results
The results indicate that the linear SVM was notably underwhelming, attributed to the non-linear separability of the data. Its performance lagged behind even random guessing. The focal metric here is the `f1_score` owing to the uneven class distribution. In most models, the f1_score hovered around 0.4—a commendable score given the prediction of 10 classes and a blind hit probability of roughly 0.1.

## Summary
In essence, factors like the game's name length, its launch year, and gameplay type can predict its popularity to some degree. Yet, this isn't a foolproof method, as my models didn't fare particularly well. Important factors possibly missing from the dataset, such as marketing strategies, game playability, and the platforms on which the game was available, presumably have a considerable influence.
