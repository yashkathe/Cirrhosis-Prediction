# Cirrhosis Prediction Using Neural Networks

## Table of Content

- [Cirrhosis Prediction Using Neural Networks](#cirrhosis-prediction-using-neural-networks)
  - [Table of Content](#table-of-content)
  - [Overview](#overview)
    - [What is Cirrhosis?](#what-is-cirrhosis)
  - [Files](#files)
    - [Neural Network From Scratch](#neural-network-from-scratch)
    - [Neural Network Using PyTorch](#neural-network-using-pytorch)
    - [Random Forest Implementation](#random-forest-implementation)
  - [Notes on How Neural Network Works (From Scratch)](#notes-on-how-neural-network-works-from-scratch)
  - [Extra](#extra)

## Overview

In this project, I have developed a predictive model to classify cirrhosis into
four categories using a neural network built with PyTorch.

I'm using the
[Cirrhosis Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset/data).

### What is Cirrhosis?

Cirrhosis is a chronic liver disease characterized by scarring (fibrosis) of the
liver tissue, leading to impaired liver function.  
It is commonly caused by long-term liver damage from factors like alcohol abuse,
hepatitis, and fatty liver disease.  
Early detection and classification of cirrhosis stages are essential for timely
intervention.

<img src="https://www.startstemcells.com/wp-content/uploads/2024/07/liver-2.jpg" height="300" alt="Cirrhosis stages">

_Credits to the respective owner of the image_

## Files

### Neural Network From Scratch

The files for this section include complete data preprocessing steps:

1. Drop columns with excessive missing values
2. Fill rows with missing values
3. Data mapping
4. Handle outliers
5. Normalize the data
6. Oversampling with SMOTE

[Shallow Neural Network Using NumPy Only](./from_scratch_neural_network.ipynb)  
=> Accuracy = 56%

![Plot for Neural Network from Scratch](./readme_content/from_scratch_plot.png)

[Shallow Neural Network With Updated Hyperparameters](./from_scratch_neural_network_update_hparams.ipynb)  
=> **Accuracy = 66%**

- Updated hyperparameters and the size of the hidden layer
- Broke down the backpropagation function into individual functions

![Plot for Neural Network With Updated Hyperparameters](./readme_content/from_scracth_plot_2.png)

### Neural Network Using PyTorch

[Neural Network With Gradient Descent](./cirrhosis_prediction_pytorch_gd.ipynb)

![Accuracy Plot](./readme_content/accuracy_1.png)  
![Loss Plot](./readme_content/loss_1.png)

[Neural Network With Stochastic Gradient Descent](./cirrhosis_prediction_pytorch_batch_sgd.ipynb)

![Accuracy Plot](./readme_content/accuracy_2.png)  
![Loss Plot](./readme_content/loss_2.png)

[Neural Network With Stochastic Gradient Descent and Dropout Layers](./cirrhosis_prediction_pytorch_sgd_and_dropout.ipynb)

![Accuracy Plot](./readme_content/accuracy_3.png)  
![Loss Plot](./readme_content/loss_3.png)

### Random Forest Implementation

[Random Forest With 275 Estimators](./random_forest.ipynb)  
=> Accuracy = 44%

## Notes on How Neural Network Works (From Scratch)

![Notes Page 1](./readme_notes_for_nn_from_scratch/NOTES_page-0001.jpg)  
![Notes Page 2](./readme_notes_for_nn_from_scratch/NOTES_page-0002.jpg)  
![Notes Page 3](./readme_notes_for_nn_from_scratch/NOTES_page-0003.jpg)  
![Notes Page 4](./readme_notes_for_nn_from_scratch/NOTES_page-0004.jpg)  
![Notes Page 5](./readme_notes_for_nn_from_scratch/NOTES_page-0005.jpg)  
![Notes Page 6](./readme_notes_for_nn_from_scratch/NOTES_page-0006.jpg)  
![Notes Page 7](./readme_notes_for_nn_from_scratch/NOTES_page-0007.jpg)  
![Notes Page 8](./readme_notes_for_nn_from_scratch/NOTES_page-0008.jpg)  
![Notes Page 9](./readme_notes_for_nn_from_scratch/NOTES_page-0009.jpg)  
![Notes Page 10](./readme_notes_for_nn_from_scratch/NOTES_page-0010.jpg)  
![Notes Page 11](./readme_notes_for_nn_from_scratch/NOTES_page-0011.jpg)  
![Notes Page 12](./readme_notes_for_nn_from_scratch/NOTES_page-0012.jpg)  
![Notes Page 13](./readme_notes_for_nn_from_scratch/NOTES_page-0013.jpg)

[Download the Whole PDF](NOTES.pdf)

## Extra

Open an issue if there are any improvements or errors in the code and notes.

⭐ Star the repository if you like the notes and approach.
