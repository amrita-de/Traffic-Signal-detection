Traffic Sign Detection Using CNN

This project implements a Traffic Sign Detection system using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The model is trained on the Traffic Sign Dataset from Kaggle, achieving 98.89% accuracy on the test set. The system is designed for classifying traffic signs, with applications in autonomous driving and advanced driver-assistance systems (ADAS).

Project Overview

This project uses a CNN to classify traffic signs from images, enabling automated recognition for real-world applications. The model is trained on a Kaggle dataset derived from the German Traffic Sign Recognition Benchmark (GTSRB), which includes images of 58 different traffic sign classes. The project provides scripts for training the model and classifying new images, making it easy to integrate into larger systems.

Features

High Accuracy: Achieves 98.89% test accuracy on the Kaggle Traffic Sign Dataset.
CNN-Based: Employs convolutional layers, pooling, and dense layers for robust feature extraction and classification.
Data Preprocessing: Includes normalization and data augmentation to handle variations in lighting, angles, and image quality.
Inference Pipeline: Allows users to upload images for real-time traffic sign classification.

Model Architecture

The CNN architecture consists of:
Convolutional Layers: For feature extraction (edges, shapes, textures).
Max-Pooling Layers: Reduce spatial dimensions while retaining key features.
Dense Layers: Perform classification across 58 classes.
Activation Functions: ReLU for hidden layers, softmax for output.
Dropout: Reduces overfitting during training.

Results

Test Accuracy: 98.89% on the Kaggle Traffic Sign Dataset test set.
![Screenshot 2025-06-30 211439](https://github.com/user-attachments/assets/8f3809ef-4782-498c-9b44-aa66742a341b)

