# Pneumonia Classification from Chest X-ray Images Using MobileNetV2

## Overview
This project classifies chest X-ray images as Pneumonia or Normal using deep learning. The dataset is from Kaggle and contains labeled images for training and testing.

MobileNetV2 is used as a base model with transfer learning. The model is fine-tuned with additional dense layers for binary classification.

## Goals
- Download and preprocess the Kaggle chest X-ray dataset.
- Train a convolutional neural network (MobileNetV2) to classify images.
- Evaluate model performance with accuracy and ROC curves.

## Tools
- Python (tensorflow, keras, matplotlib)
- Image preprocessing with ImageDataGenerator
- Deep learning with MobileNetV2 and Keras Sequential API

## Results
- Training and validation accuracy were monitored over 5 epochs.
- Model achieved reasonable performance, though train and validation accuracy may differ due to dataset size and augmentation.
- ROC curves provide insight into model discrimination between Pneumonia and Normal classes.

## Conclusion
The Kaggle chest X-ray dataset was successfully loaded and preprocessed. MobileNetV2 transfer learning allowed the model to classify Pneumonia images with good performance. This project demonstrates the workflow of data loading, preprocessing, deep learning training, evaluation, and visualization for medical image classification.
