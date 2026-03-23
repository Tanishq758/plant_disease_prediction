# plant_disease_prediction
Plant Disease Classification using CNN and TensorFlow  A deep learning model built using TensorFlow to classify plant leaf diseases across 38 classes with ~97% validation accuracy.

# 🌿 Plant Disease Classification using CNN

This project implements a **Convolutional Neural Network (CNN)** to classify plant diseases from leaf images.  
The model is trained using **TensorFlow / Keras** and can identify **38 different plant disease classes** based on leaf images.

The goal of this project is to build an accurate image classification model that can detect plant diseases automatically using deep learning.

---

## 📌 Features

- Image classification using **Convolutional Neural Networks**
- Supports **38 plant disease classes**
- Built with **TensorFlow and Keras**
- Image preprocessing and dataset loading using `image_dataset_from_directory`
- High validation accuracy (~97%)
- Model export for deployment

---

## 🧠 Model Architecture

The model is based on a **CNN architecture** consisting of:

- Convolutional Layers
- MaxPooling Layers
- Global Average Pooling
- Dense Layers
- Softmax output layer for multi-class classification

Input Shape:
(1,128,128,3)

## 📊 Model Performance

| Metric | Value |
|------|------|
Training Accuracy | **96.29%**
Validation Accuracy | **96.98%**
Training Loss | 0.117
Validation Loss | 0.095

The model demonstrates strong performance and good generalization across the dataset.

