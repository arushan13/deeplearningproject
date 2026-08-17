# 🐕 Dog Vision - Dog Breed Image Classification

A deep learning image classification project that uses **TensorFlow/Keras** and **transfer learning** to classify images into **120 different dog breeds**.

The model uses a pretrained **MobileNetV2** architecture as a feature extractor and a custom classification layer to predict the breed of a dog from an image.

## 📌 Project Overview

The goal of this project was to build an end-to-end image classification pipeline capable of identifying dog breeds from images.

The project covers:

- Image preprocessing
- Creating training and validation datasets
- Batch processing with `tf.data`
- Transfer learning with MobileNetV2
- Building a custom classification layer
- Model training and validation
- Performance evaluation
- TensorBoard monitoring

The final model achieved approximately **85% validation accuracy** across 120 dog breeds.

## 🧠 Model Architecture

The project uses **transfer learning** with a pretrained MobileNetV2 model.

### Architecture

```text
Input Image
     ↓
Image Preprocessing
     ↓
Pretrained MobileNetV2
     ↓
Feature Extraction
     ↓
Dense Layer
     ↓
Softmax Activation
     ↓
120 Dog Breed Predictions


🛠️ Technologies Used
Python
TensorFlow
Keras
NumPy
Pandas
Matplotlib
TensorBoard
Google Colab


