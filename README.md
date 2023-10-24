# Diabetes Classification Project with Keras and TensorFlow

## Overview

This repository contains a machine learning project for diabetes classification using the Keras API for TensorFlow 2.0. The goal is to build a classification model to predict whether an individual has diabetes or not based on various health-related features.

## Data Source

The dataset used for this project is sourced from a Kaggle dataset, which can be found here: [Diabetes Data Set](https://www.kaggle.com/datasets/mathchi/diabetes-data-set).

### Feature Columns

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration at 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)

### Target Variable

- **Outcome**: Class variable (0 or 1), where 1 indicates "tested positive for diabetes."

## Project Details

- Number of Instances: 768
- Number of Features: 8 plus target variable
- Missing Attribute Values: Yes
- Class Distribution: The class value 1 is interpreted as "tested positive for diabetes."

## Repository Contents

This repository contains the code and Jupyter Notebook for the diabetes classification project. You can explore the data, data preprocessing, model building, and evaluation within the Jupyter Notebook.

Feel free to clone or fork this repository for your own use or exploration.

## Model Performance

My proposed Multi-Layer Perceptron (MLP) model, which incorporates dropout layers for regularization, achieved an impressive accuracy of 91% on the test data. This demonstrates the effectiveness of the model in accurately classifying individuals with and without diabetes.

The model was trained on the provided dataset and evaluated using appropriate metrics to ensure its reliability and effectiveness.

## Acknowledgments

This project is for educational and learning purposes. We acknowledge the data source from Kaggle and appreciate the open-source contributions of the data science community.

## Contact

For questions or collaboration, you can reach out to me on GitHub or connect on LinkedIn.

[LinkedIn](https://www.linkedin.com/in/yutong-xie-b5a8a6233/)
[GitHub](https://github.com/yutongxie58)
