# Enhancing Fake News Detection Through Machine Learning and Transfer Learning Methods

This repository contains the code for our Springer Nature book chapter on fake news detection.

## Overview

The project explores fake news classification using a hybrid machine learning pipeline.  
We experimented with traditional machine learning models and deep learning approaches to compare performance and understand the effect of preprocessing, feature tuning, and model choice.

## Research Summary

Our study focused on detecting fake news using:

- Logistic Regression
- Support Vector Machine (SVM)
- Bi-LSTM with transfer learning

After extensive preprocessing and dataset tuning, Logistic Regression achieved the highest accuracy at **90.62%**.  
This reinforced an important lesson: clean data and careful feature preparation can matter more than model complexity.

## Key Contributions

- Built a fake news detection pipeline for text classification.
- Compared classical machine learning and deep learning models.
- Applied preprocessing and feature engineering to improve performance.
- Evaluated model results with a focus on practical effectiveness.

## Repository Contents

- `CSE475_Fake_News_Detection.ipynb` — main notebook with code and experiments.
- `README.md` — project documentation.

## Workflow

1. Load the dataset.
2. Clean and preprocess text.
3. Extract features.
4. Train multiple models.
5. Evaluate and compare results.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras
- NLP techniques

## Results

The best-performing model in this project was Logistic Regression, which achieved **90.62% accuracy** after preprocessing and tuning.

## Citation

If you use this work, please cite our Springer Nature chapter:

**Enhancing Fake News Detection Through Machine Learning and Transfer Learning Methods**  
DOI: `10.1007/978-981-96-6053-7_28`
