# Digit Recognition with Deep Learning

## 🎯 Project Description
This project implements a deep learning model capable of recognizing handwritten digits (0–9) from images.  
The model is trained on the **MNIST dataset**, a benchmark dataset widely used in computer vision.

## 📊 Dataset
- **MNIST**: 70,000 grayscale images of handwritten digits (28x28 pixels).
- Split: 60,000 training images, 10,000 test images.

## 🧠 Model Architecture
The model is a Convolutional Neural Network (CNN) with the following layers:
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten → Dense(128, ReLU) → Dense(10, Softmax)

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/username/digit-recognition-deeplearning.git
   cd digit-recognition-deeplearning
