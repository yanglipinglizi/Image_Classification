﻿# Image Classification (Vehicles, Dogs, Food)
## 1. Overview
This project aims to identify and categorize images into three distinct classes: vehicles, dogs, and food using a Convolutional Neural Network (CNN).
 
## 2. Method Used

### ResNet-18 Architecture
ResNet-18 is a convolutional neural network designed for image classification, featuring 18 layers including an initial convolution layer, four sets of residual blocks (each with 2 blocks), and a fully connected output layer. It utilizes skip connections to facilitate training deeper networks and addresses the vanishing gradient problem, making it efficient and effective for various computer vision tasks.
<p align="center">
  <img src="images/resnet.png" alt="VGG-16 Blocks" width="500"/>
</p>

### Other Methods 
##### L2 Regularization
L2 regularization, also known as weight decay, is a technique used to prevent overfitting in machine learning models. It adds a penalty to the loss function based on the squared values of the model's weights. This discourages large weights, promoting simpler models that generalize better to unseen data. L2 regularization is commonly applied in linear regression, neural networks, and various machine learning algorithms.
##### Early Stopping
Early stopping is a regularization technique used to prevent overfitting during the training of machine learning models. It involves monitoring the model's performance on a validation dataset while training. Training is halted when the model's performance on the validation set begins to degrade, indicating that further training may lead to overfitting. This helps to ensure that the model retains its ability to generalize well to unseen data, balancing training time and model performance effectively. Early stopping is commonly used in various machine learning and deep learning applications.

## 3. Result
### ResNet-18
Precision: 0.89
Recall: 0.88
F1 Score: 0.88
<p align="center">
  <img src="images/loss1.png" alt="Accuracy" width="365" style="display:inline-block; margin-right: 10px;"/>
  <img src="images/accuracy1.png" alt="Loss" width="350" style="display:inline-block;"/>
</p>

### ResNet-18 + L2 Regularization
Precision: 0.88
Recall: 0.88
F1 Score: 0.88
<p align="center">
  <img src="images/loss2.png" alt="Accuracy" width="380" style="display:inline-block; margin-right: 10px;"/>
  <img src="images/accuracy2.png" alt="Loss" width="400" style="display:inline-block;"/>
</p>

### ResNet-18 + L2 Regularization + Early Stopping
Precision: 0.90
Recall: 0.89
F1 Score: 0.89
<p align="center"> 
    <img src="images/accuracy3.png" alt="Loss" width="750"/>
</p>
