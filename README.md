# Fruit Classification using EfficientNetB1 🍎

This repository contains the code and resources for a fruit classification project using the **EfficientNetB1** deep learning model. The goal of this project is to classify different types of fruits based on image data with high accuracy while maintaining an efficient computational performance.

## [1] Overview

In this project, we implement a fruit classification model using **EfficientNetB1**, a powerful and efficient convolutional neural network. The model is trained on a dataset of various fruit images and is capable of distinguishing between multiple fruit types with high accuracy.

## [2] Dataset

This dataset contains images of whole fruit and pieces of fruit consisting of 44 fruit classes, such as:
* 🍎 Apple (Apel)
* 🥑 Avocado (Alpukat)
* 🍌 Banana (Pisang)
* 🍒 Cherries (Ceri)
* 🥥 Coconut (Kelapa)
* 🍇 Grape (Anggur)
* 🍋 Lemon (Lemon)
* 🥭 Mangga (Mangga)
* 🍉 Watermelon (Semangka) etc.

Dataset link = https://www.kaggle.com/datasets/keynatwgm/fruits-nutrionix

## [3] Model Architecture

EfficientNetB1 is part of the EfficientNet family of models, which are known for their balance between accuracy and computational efficiency. The model scales up neural networks in a more structured way by uniformly scaling network width, depth, and resolution, leading to better performance with fewer resources.

## [4] Why EfficientNetB1?

We chose EfficientNetB1 for this project for the following reasons:
1. Efficiency: EfficientNetB1 offers a great trade-off between model size and accuracy. It is designed to achieve better accuracy with fewer parameters compared to traditional models like ResNet or VGG.
2. Scalability: EfficientNetB1 is part of a scalable architecture that allows us to easily adapt the model to different computational constraints. For fruit classification, EfficientNetB1 provides a suitable balance between speed and performance.
3. Accuracy: With its optimized architecture, EfficientNetB1 is capable of delivering high classification accuracy on image data, making it ideal for tasks like fruit classification where precise predictions are needed.

## [5] Requirements

* TensorFlow version: 2.15.0
* Keras version: 2.15.0
* NumPy version: 1.25.2
* Matplotlib version: 3.7.1
* Python 3 version: 3.10.12 
