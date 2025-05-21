# Handwritten Letter Recognition – Kaggle Competition

This repository contains my solution for a Kaggle image classification competition (www.kaggle.com/competitions/kyrgyz-language-hand-written-letter-recognition/overview/) where the goal was to identify single handwritten letters from grayscale images.

## Result
- **Second Score:** 0.96069
- **Evaluation Metric:** Categorization Accuracy  
  > Accuracy = Correct Predictions / Total Predictions

## Problem Description
Given a 50x50 grayscale image of a handwritten letter, the task was to classify it into one of 37 categories (A–Z and 0–9 excluding confusing characters).

## My Approach
- Used a CNN (Convolutional Neural Network) built with TensorFlow/Keras
- Applied Batch Normalization and Dropout to reduce overfitting
- Trained on preprocessed grayscale images with shape `(50, 50, 1)`
- Used `categorical_crossentropy` loss and `Adam` optimizer

## Tech Stack
- TensorFlow / Keras
- NumPy / pandas
- scikit-learn
- Matplotlib
