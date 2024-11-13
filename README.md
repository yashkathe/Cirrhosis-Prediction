# Cirrhosis Prediction Using Neural Networks

<img src="https://www.startstemcells.com/wp-content/uploads/2024/07/liver-2.jpg" height="300" alt="cirrhosis stages">

## Project Overview

This project aims to develop a predictive model to classify cirrhosis into three
categories using a neural network built with PyTorch. By using the
[Cirrhosis Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset/data).

## What is Cirrhosis?

Cirrhosis is a chronic liver disease characterized by scarring (fibrosis) of the
liver tissue, leading to impaired liver function. Commonly caused by long-term
liver damage from factors like alcohol abuse, hepatitis, and fatty liver
disease, cirrhosis can progress to life-threatening complications if left
untreated. Early detection and classification of cirrhosis stages are essential
for timely intervention and management.

## Dataset Information

The dataset used in this project comes from Kaggle and includes medical records
of patients with liver conditions. Key attributes in the dataset include:

- **Age**: Age of the patient
- **Gender**: Male or Female
- **Bilirubin Levels**: A measure of liver function
- **Albumin Levels**: Protein produced by the liver, indicative of liver health
- **Ascites**: Presence of fluid in the abdomen, often associated with severe
  liver disease
- **Prothrombin**: Coagulation indicator, reflecting liver functionality

Each record is labeled with a cirrhosis stage category, making this a multiclass
classification task.

## Approach

- **Model Development**: Two neural network models will be implemented:
  - **Neural Network from Scratch**: Built from scratch using only NumPy to
    understand the fundamental workings of each network component.
  - **PyTorch Neural Network**: Developed with PyTorch to leverage its deep
    learning capabilities and optimized operations.
- **Comparison**: The performance of the handwritten model will be compared
  against the PyTorch implementation to evaluate accuracy, efficiency, and
  computational complexity.
