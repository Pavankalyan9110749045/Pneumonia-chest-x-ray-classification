# Pneumonia-chest-x-ray-classification
This project builds a deep learning model using MobileNetV2 to detect Pneumonia from chest X-ray images.
# Pneumonia Detection using MobileNetV2
# Project Description

This project builds a deep learning model using MobileNetV2 to detect Pneumonia from chest X-ray images. It leverages transfer learning to achieve high accuracy in classifying images as NORMAL or PNEUMONIA.

# Objectives

-Classify chest X-ray images into NORMAL and PNEUMONIA

-Improve diagnostic accuracy using deep learning

-Handle class imbalance effectively

-Use transfer learning for better performance

# Technologies Used

-Python

-TensorFlow / Keras

-NumPy

-Matplotlib

-Scikit-learn

# Dataset

-The dataset contains chest X-ray images organized into:

-Train

-Validation (Val)

-Test

# Each folder has two classes:

* NORMAL

*PNEUMONIA

# Model Architecture

-Pre-trained MobileNetV2 (Transfer Learning)

-Frozen base layers + fine-tuned layers

-Fully connected layers for classification

-Sigmoid activation for binary output

# Workflow

Data Collection
     ↓
Data Preprocessing
     ↓
Data Augmentation
     ↓
Model Training (MobileNetV2)
     ↓
Validation
     ↓
Testing & Evaluation
     ↓
Prediction

# Features

-Uses transfer learning for faster training

-Handles class imbalance using class weights

-Data augmentation improves generalization

-High accuracy on unseen data

# Results

-Accurate classification of X-ray images

-Improved performance using pre-trained model

-Reliable detection of pneumonia cases

# Conclusion

This project demonstrates the effectiveness of deep learning and transfer learning in medical image classification. The model provides a reliable solution for detecting pneumonia and can assist healthcare professionals in faster diagnosis.
