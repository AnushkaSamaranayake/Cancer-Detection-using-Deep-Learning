# Cancer-Detection-using-Deep-Learning

A simple Convolutional Neural Network (CNN) model to detect brain tumors from MRI images. This project aims to provide a straightforward and effective approach to brain tumor classification, helping in the early diagnosis of brain-related diseases.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)

## Introduction

Brain tumors can be life-threatening if not diagnosed early. This project utilizes a deep learning approach using a CNN model to detect brain tumors from MRI images. The model is trained on a dataset of labeled images, classifying them as either having a tumor or not.

## Dataset

The model is trained using a dataset of brain MRI images. Each image is labeled as having a tumor or not. The dataset should be organized in the following structure:
https://github.com/AnushkaSamaranayake/Cancer-Detection-using-Deep-Learning/tree/main/Brain%20Tumor%20Data%20Set/Brain%20Tumor%20Data%20Set


Ensure that your dataset is preprocessed appropriately (resized, normalized) before feeding it into the model.

## Model Architecture

The model is a simple CNN consisting of the following layers:

- Convolutional layers with ReLU activation
- MaxPooling layers
- Fully connected dense layers
- Dropout for regularization
- Output layer with softmax activation for classification

## Transfer Learning

This model is trained using a pre-trained model to enhance the accuracy of the predictions. MobilNet pre-trained model is used here in order to enhance the performance and, this will increase the accuracy of the model more than 90%
 
