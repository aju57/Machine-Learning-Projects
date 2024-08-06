# Review Classification Project

## Overview

This project involves classifying reviews from the Yelp dataset into one of five star ratings (1 to 5 stars) using machine learning techniques. The project explores different methods for feature engineering, handles class imbalance, and applies various machine learning algorithms to achieve better classification performance.

## Table of Contents

- [Overview](#overview)
- [Data](#data)

- [Handling Class Imbalance](#handling-class-imbalance)
- [Model Training](#model-training)
- [Evaluation](#evaluation)




## Data

The dataset used for this project is the Yelp review dataset. It contains user reviews with ratings ranging from 1 to 5 stars. 

### Data Files

- `data/yelp.csv`: The CSV file containing the review text and ratings.



## Handling Class Imbalance

To address class imbalance in the dataset, the following techniques were applied:

- **SMOTE (Synthetic Minority Over-sampling Technique)**: Generated synthetic samples for minority classes.
- **Random Undersampling**: Reduced the number of samples in majority classes.
- **SMOTE + Tomek Links**: Combined SMOTE with Tomek Links to handle both class imbalance and noise.

## Model Training

Models were trained using the following approaches:

- **Multinomial Naive Bayes**: Applied to the TF-IDF matrix and additional features.
- **Evaluation Metrics**: Performance evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

## Evaluation

Model performance was evaluated based on:

- **Classification Report**: Includes precision, recall, F1-score for each class.
- **Confusion Matrix**: Provides insight into classification errors.



