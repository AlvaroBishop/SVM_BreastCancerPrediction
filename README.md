# SVM_BreastCancerPrediction
This project features a Support Vector Machine (SVM) classification model that predicts whether a breast cancer diagnosis is benign or malignant based on multiple observations and features. The primary objective is to assist in the early detection of breast cancer by leveraging machine learning techniques.

## Project Overview
Early detection of breast cancer is crucial for effective treatment and improved patient outcomes. This project employs a Support Vector Machine (SVM) classification model to analyze various features extracted from breast cancer biopsies. The model aims to classify diagnoses as either benign or malignant, providing valuable insights for medical professionals and researchers.

## Data
The dataset used in this project is sourced from the Breast Cancer Wisconsin (Diagnostic) dataset, available at [https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic) It comprises 30 features, including measurements such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension. These features are essential in characterizing cell nuclei from breast biopsies.

Datasets are linearly separable using all 30 input features.

Number of Instances: 569

Target classes:

- Malignant
- Benign
 
## Model Training and Prediction
The SVM model is trained on the provided dataset to learn the patterns and relationships between the input features and the corresponding diagnosis labels. Once trained, the model can predict whether a new biopsy observation is likely to be benign or malignant based on the learned patterns.



