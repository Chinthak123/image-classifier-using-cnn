# image-classifier-using-cnn
🖼️ Image Classification using Neural Networks (MNIST)

This project demonstrates a basic image classification model built using TensorFlow and Keras.
The model is trained on the MNIST dataset to classify handwritten digits (0–9).

📌 Project Overview

Dataset: MNIST Handwritten Digits

Task: Multi-class image classification

Model Type: Fully Connected Neural Network

Framework: TensorFlow / Keras

Environment: Jupyter Notebook

The goal of this project is to understand the end-to-end workflow of a machine learning model, including data loading, preprocessing, model building, training, and evaluation.

🧠 Model Architecture

Input Layer: Flattened 28×28 grayscale images

Hidden Layer:

Dense layer with 128 neurons

ReLU activation

Output Layer:

Dense layer with 10 neurons

Softmax activation

🛠️ Technologies Used

Python

TensorFlow

Keras

NumPy

Jupyter Notebook

📂 Dataset Details

Training samples: 60,000 images

Testing samples: 10,000 images

Image size: 28 × 28 pixels

Labels: Digits from 0 to 9

The dataset is loaded directly using:
