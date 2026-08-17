# 🐱🐶 Cats vs Dogs Image Classification using CNN

A Deep Learning project that classifies images as either a **Cat** or a **Dog** using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## 📌 Project Objective

The objective of this project is to understand how Convolutional Neural Networks can be used for binary image classification.

The model learns visual features from cat and dog images and predicts the class of a new unseen image.

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Convolutional Neural Network (CNN)
- Google Colab
- Kaggle Dataset

## 📊 Dataset

The project uses a Cats and Dogs dataset containing approximately **25,000 images**.

- Cat images: 12,499
- Dog images: 12,499
- Training: 80%
- Validation: 20%

Images are resized to:

```text
180 × 180 × 3

🧠 Model Architecture
Input Image
     ↓
Data Augmentation
     ↓
Rescaling
     ↓
Conv2D - 32 filters
     ↓
MaxPooling
     ↓
Conv2D - 64 filters
     ↓
MaxPooling
     ↓
Conv2D - 128 filters
     ↓
MaxPooling
     ↓
GlobalAveragePooling2D
     ↓
Dense - 128 neurons
     ↓
Dropout - 0.5
     ↓
Sigmoid
     ↓
Cat / Dog

🔧 Techniques Used
Data Augmentation
 *Random Horizontal Flip
 *Random Rotation
 *Random Zoom
Regularization
 *Dropout
 *Early Stopping
