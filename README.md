# Deep Learning Lung and Colon Cancer Classification

This repository contains the project work focusing on classifying lung and colon cancer histopathological images from the LC25000 dataset using various deep learning techniques.

## Project Overview

The goal of this project is to develop and optimize a Convolutional Neural Network (CNN) to perform multi-class classification on the Lung and Colon Cancer Histopathological Image Dataset (LC25000). Key components of the project include:

- Data Preprocessing
- Exploratory Data Analysis
- Baseline CNN Model Development
- Model Optimization and Fine-Tuning
- Transfer Learning with Pre-trained Models
- Model Evaluation and Comparison

## Dataset

The LC25000 dataset consists of histopathological images of lung and colon cancer, with a balanced class distribution of 5,000 samples per category. Images were resized to 120x120 pixels for computational efficiency.

## Models and Techniques

### Baseline Model

- Initial CNN architecture
- Performance issues such as overfitting were identified

### Improved (Fine-tuned) Model

- Increased network depth with more convolutional layers
- Applied dropout and L2 regularization
- Adjusted learning rate and hyperparameters
- Achieved better generalization and accuracy

### Transfer Learning Model

- Used VGG16 as a feature extractor
- Achieved high accuracy with fewer trainable parameters

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC Curves
- Confusion Matrices

## Results

The fine-tuned and transfer learning models showed significant improvements over the baseline model, achieving accuracy up to 97%.

## References

- LC25000 Dataset: *Lung and Colon Cancer Histopathological Image Dataset*. [Link](https://github.com/tampapath/lung_colon_image_set/)
- Masud, M. et al. (2021). A machine learning approach to diagnosing lung and colon cancer using a deep learning-based classification framework. *Sensors*, 21(3), 1–21. 
- Kumar, N. et al. (2022). An empirical study of handcrafted and dense feature extraction techniques for lung and colon cancer classification from histopathological images. *Biomedical Signal Processing and Control*, 75, 103550.
- Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. ”Imagenet classification with deep convolutional neural networks.” Communications of the ACM 60.6 (2017): 84-90.



