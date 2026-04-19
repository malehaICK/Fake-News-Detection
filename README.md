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

## Tools

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-58a6ff?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-58a6ff?style=for-the-badge&logo=tensorflow&logoColor=white" />
</p>

## Model Performance

<p align="center">
  <img src="https://img.shields.io/badge/Logistic_Regression-90.62%25-58a6ff?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/SVM-88.00%25-38d9a9?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Bi--LSTM-89.40%25-f97583?style=for-the-badge&labelColor=0d1117" />
</p>

## Results
Best Model is <img src="https://img.shields.io/badge/Logistic_Regression-90.62%25-58a6ff?style=for-the-badge&labelColor=0d1117" />
## Citation

If you use this work, please cite our Springer Nature chapter:

**Enhancing Fake News Detection Through Machine Learning and Transfer Learning Methods**  
DOI: `10.1007/978-981-96-6053-7_28`
