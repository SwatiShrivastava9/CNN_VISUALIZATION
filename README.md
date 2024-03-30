# CNN_VISUALIZATION

This repository contains code for training a Convolutional Neural Network (CNN) on the MNIST dataset for image classification. Additionally, it includes the implementation of GradCAM (Gradient-weighted Class Activation Mapping) for interpreting the CNN's predictions.

Installation
To start, install the pytorch-gradcam module:
!pip install -q grad-cam==1.4.3

Overview
Following key steps involved:

Data Loading and Preprocessing: The MNIST dataset is loaded and preprocessed. It is split into training, validation, and test sets.
Model Training: A CNN model is defined and trained using the training data. The training process is monitored for both training and validation loss.
Evaluation: The trained model is evaluated on both the training and validation sets to assess its performance using classification reports.
GradCAM Interpretation: GradCAM is applied to interpret the model's predictions. GradCAM generates heatmaps to visualize the regions of the input images that contribute most to the model's decision-making process.

Code Structure
Data Preparation: Loading and preprocessing MNIST dataset, split into training, validation, and test sets.
Model Definition: CNN model definition for image classification.
Training Loop: Training the CNN model on the training data.
Evaluation: Evaluating the trained model on training and validation sets.
GradCAM Interpretation: Applying GradCAM to interpret model predictions.

Conclusion
This demonstrates the process of training a CNN model for image classification on the MNIST dataset and interpreting its predictions using GradCAM. By visualizing the regions of the input images that contribute to the model's decisions, we gain insights into the model's behavior and understand which parts of the images are most important for classification.
