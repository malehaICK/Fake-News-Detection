
Enhancing Fake News Detection Through Machine Learning and Transfer Learning Methods

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

- `notebooks/CSE475_Fake_News_Detection.ipynb` — main notebook with code and experiments.
- `README.md` — project documentation.

## Workflow

```mermaid
flowchart LR
    A[Load Dataset] --> B[Text Cleaning & Preprocessing]
    B --> C[Feature Extraction]
    C --> D[Model Training]
    D --> E[Evaluation]
    E --> F[Model Comparison & Selection]
```

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
<b><img src="https://img.shields.io/badge/Best Model Logistic_Regression-90.62%25-58a6ff?style=for-the-badge&labelColor=0d1117" /></b>
## Citation

If you use this work, please cite our Springer Nature chapter:

**Enhancing Fake News Detection Through Machine Learning and Transfer Learning Methods**  
DOI: `10.1007/978-981-96-6053-7_28`



## Repository Structure

```text
Fake-News-Detection/
├── notebooks/
│   └── CSE475_Fake_News_Detection.ipynb   # preprocessing, models and experiments
├── LICENSE
└── README.md
```

## How to Run

Step 1. Clone the repository:

```bash
git clone https://github.com/malehaICK/Fake-News-Detection.git
cd Fake-News-Detection
```

Step 2. Install the dependencies:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib jupyter
```

Step 3. Open the notebook and run the cells in order:

```bash
jupyter notebook notebooks/CSE475_Fake_News_Detection.ipynb
```

The notebook was developed in Google Colab, so you can also upload it there. Check the data loading cell at the top for the dataset it expects and adjust the file path if you run it locally.

## Author

Maleha Israt Chowdhury. [Portfolio](https://malehaisratchowdhury.netlify.app/)

## License

Released under the MIT License. See the `LICENSE` file.
