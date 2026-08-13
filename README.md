# handbag-vs-shoe-image-classification
# 👜👟 Handbag vs Shoe Image Classification using Transfer Learning

An image classification project that distinguishes between handbags and shoes using deep learning. The project explores convolutional neural networks, data augmentation, Vision Transformers, and transfer learning with a pretrained ResNet50 model.

## 📌 Project Overview

This project demonstrates an end-to-end image classification workflow using a small dataset of handbag and shoe images.

Since the dataset contains only a limited number of images, the project explores different deep learning approaches, including:

- Convolutional Neural Network (CNN)
- Data augmentation
- Vision Transformer (ViT)
- Transfer learning using ResNet50
- Feature extraction using a pretrained ImageNet model
- Dropout regularization
- Webcam-based image prediction

The final transfer-learning approach uses a pretrained ResNet50 network to extract image features and a custom neural network classification head to classify images as either a handbag or a shoe.

## 🎯 Objective

The objective is to build a binary image classification model capable of identifying whether an input image contains a:

- 👜 Handbag
- 👟 Shoe

## 📂 Dataset

The project uses a small collection of web-scraped color images containing two classes:

- `handbags`
- `shoes`

Approximately 100 images were collected for each class.

The dataset is divided into:

- Training set: 50 images per class
- Validation set: 25 images per class
- Test set: remaining images

Images are resized to:

```text
224 × 224 × 3
