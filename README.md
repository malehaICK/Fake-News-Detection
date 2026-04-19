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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fake News Detection Results</title>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0d1117;
      color: white;
      margin: 0;
      padding: 40px;
    }
    .chart-container {
      max-width: 900px;
      margin: auto;
      background: #161b22;
      padding: 24px;
      border-radius: 12px;
    }
  </style>
</head>
<body>
  <div class="chart-container">
    <canvas id="modelChart"></canvas>
  </div>

  <script>
    const ctx = document.getElementById('modelChart').getContext('2d');
    new Chart(ctx, {
      type: 'bar',
      data: {
        labels: ['Logistic Regression', 'SVM', 'Bi-LSTM'],
        datasets: [{
          label: 'Accuracy (%)',
          data: [90.62, 88.00, 89.40],
          backgroundColor: ['#5B8FF9', '#61DDAA', '#F6BD16'],
          borderWidth: 1
        }]
      },
      options: {
        responsive: true,
        plugins: {
          legend: {
            labels: {
              color: 'white'
            }
          },
          title: {
            display: true,
            text: 'Fake News Detection Model Comparison',
            color: 'white',
            font: {
              size: 20
            }
          }
        },
        scales: {
          x: {
            ticks: {
              color: 'white'
            },
            grid: {
              color: '#30363d'
            }
          },
          y: {
            beginAtZero: true,
            max: 100,
            ticks: {
              color: 'white'
            },
            grid: {
              color: '#30363d'
            }
          }
        }
      }
    });
  </script>
</body>
</html>

## Citation

If you use this work, please cite our Springer Nature chapter:

**Enhancing Fake News Detection Through Machine Learning and Transfer Learning Methods**  
DOI: `10.1007/978-981-96-6053-7_28`
