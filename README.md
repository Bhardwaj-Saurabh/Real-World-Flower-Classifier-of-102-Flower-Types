# Real-World-Flower-Classifier-of-102-Flower-Types
This repository contains the file for building a real world flower classifier of 102 flower data using PyTorch.
![](https://github.com/Bhardwaj-Saurabh/Real-World-Flower-Classifier-of-102-Flower-Types/blob/master/102_Flower.png)

## **Author: Saurabh Bhardwaj**
## Last Updated: 05 Jan 2022

## Introduction
This Jupyter Notebook shows step-by-step guide on:

- Download the 102 flower dataset. I've used the 102 Category Flower Dataset from https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html
- Data visualisation of few categories of the flower dataset
- Using Transfer Learning for feature extraction from a pre-trained model Resnet 50.
- Using PyTorch apply Data Augementation to the data and build input pipelines for the dataset split into training, validation and test datasets.
- Build, train and evaluate the model.
- Using Callback to define early stopping threshold for model training.
- Report Model accuracy
- Make prediction with the trained model
- Save Model

## **Technology**
- Pytorch
- Transfer Learning Resnet50 pretrained model

## **Results**
The model evaluation results:
- Validation Accuracy: 0.96
- Test Accuracy: 0.95

![loss](https://github.com/Bhardwaj-Saurabh/Real-World-Flower-Classifier-of-102-Flower-Types/blob/master/model_loss.png) | ![Accuracy](https://github.com/Bhardwaj-Saurabh/Real-World-Flower-Classifier-of-102-Flower-Types/blob/master/model_acc.png)
