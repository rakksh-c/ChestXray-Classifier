# Chest X-Ray Pneumonia Classification

## Overview
This project uses deep learning and transfer learning to classify chest X-ray images into two categories: NORMAL and PNEUMONIA. The model is built using TensorFlow and MobileNetV2.

## Technologies Used
- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- Google Colab

## Dataset
The project uses the Chest X-Ray Images (Pneumonia) dataset obtained from Kaggle.

## Methodology
1. Dataset loading
2. Image preprocessing and augmentation
3. MobileNetV2 feature extraction using pretrained ImageNet weights
4. Binary classification using a sigmoid output layer
5. Model training
6. Test evaluation and classification report
7. Confusion matrix and performance visualization
8. Prediction on a new X-ray image

## Model Results
- Test Accuracy: 79.01%
- Test Loss: 0.4531

## Output
The model predicts whether an input chest X-ray image belongs to the NORMAL or PNEUMONIA category.

## Disclaimer
This project is an educational machine learning prototype and is not intended for clinical diagnosis or medical decision-making.
